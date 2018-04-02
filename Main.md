package me.games.enderdragon909;

import org.bukkit.plugin.java.JavaPlugin;

public class Main extends JavaPlugin{
	
	@Override
	public void onEnable() {
		System.out.println("(i) Olympics Plugin has been Enabled!");
		
		getCommand("olympics").setExecutor(new Commands());
	}
	
	@Override
	public void onDisable() {
		System.out.println("(i) Olympics Plugin has been Disabled!");
	}

}
