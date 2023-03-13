# ItemsLib


# What is that ?
ItemsLib, is a very useful library, it contains only one class. It makes your life easier to create your ItemStack, the methods are already created for you, just remember them


# How to use it ?

**In your plugin:**
    Exemple, You want to give an custom item to a player when connecting:



    @EventHandler public void onJoin(PlayerJoinEvent e) {
     final Player player = e.getPlayer(); 
     
     player.getInventory().addItem(ItemsBuilder.createCustomItem(Material.COMPASS, 1, "§bCustom Item", new String[] {"", "§cUse for ..."}, Enchantment.KNOCKBACK, 0));
    }

    
    

## Support

Discord: [join](https://discord.gg/KxpSxMTAxu)
