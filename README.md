# startAnyScene

This mod adds a new icon, named X FILE, to HC's computer. Clicking on it allows the player to browse and play any main questline scene or character quest scene without having to unlock it first.
![Demonstration image showing the desktop of HC's computer with the new X FILE icon.](https://raw.githubusercontent.com/mayalaran-h/startAnyScene/refs/heads/main/demo-image.PNG)

## Requirements
This mod comes packaged with the [Godot Mod Loader](https://wiki.godotmodding.com/) which is needed for the mod to function. 
The appropriate release of the mod loader is included in the <code>addons</code> directory of the mod's release.

## Installation & Modloader Setup (fresh installation, no previous mods)
1.	Extract the contents of the mod's most recent .zip release into the game's base directory. The game's base directory can be located from Steam by <code>right-clicking the game > Manage > Browse local files</code> <br />
	After extraction there should be two new directories: <code>mods</code> and <code>addons</code>. <br />
2.	Next, add a launch option in Steam by <code>right-clicking the game > Properties > General</code> in the text input box add the following:<br />
	<code>--script addons/mod_loader/mod_loader_setup.gd</code><br />
3.	Launch the game and click OK when the popup informs you that the game will restart for changes to take effect.
4.	After the game restarts, use the quit button on the main menu to close it.
5.	Now that the modloader is set up, remove the launch option by <code>right-clicking the game > Properties > General</code> and deleting the code from the text input box.
6.	The mod and modloader are now installed and the game may be launched as normal.

## If you have installed HARDCODED mods before (modloader already installed and setup)
1.	Copy the mods folder from the most recent release into the game's base directory. The game's base directory can be located from Steam by <code>right-clicking the game > Manage > Browse local files</code>
2.	Launch the game to play with mods.

## Disabling the mod
Mods can be disabled by adding <code>--disable-mods</code> to the game's launch options.
