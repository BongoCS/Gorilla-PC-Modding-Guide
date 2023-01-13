# GorillaTag PC Modding Guide

# Setting up MonkeModManager
Here is the Install Link for MonkeModManager on GitHub
https://github.com/DeadlyKitten/MonkeModManager/releases/tag/1.3.0

Monke Mod Manager is a mod installer that will install custom mods into Gorilla Tag automatically, and can be re-run in order to update the mods. Monke Mod Manager also notifies you of any updates upon launch by opening the latest release’s page if available.

You are going to want to download and install this.

#### Note: If Windows alerts you that the file is unsafe/at risk, choose to keep/run anyway. This is a false-positive.

After you’ve downloaded Monke Mod Manager, double-click the executable to run it. By default, Monke Mod Manager should automatically fill in your Gorilla Tag installation folder.

Next, you may select any mods that are listed. BepInEx is the modloader for Gorilla Tag and cannot be unchecked. To update a mod, simply select the installed mod again. If you would like to get more information on a mod, click on it then hit the View Mod Info button.

After you select the mods you would like to install/update, hit the Install/Update button to begin the process. When the status monitor in the bottom left says “Install complete!“, you’re almost there!

If it’s your first time modding (or starting with a clean install), you’ll need to launch Gorilla Tag once and close it to initialize BepInEx. You may not see any mods load the first time you launch Gorilla Tag after modding, this is normal.
After that, re-launch Gorilla Tag and if everything went well, your mods will now load into the game. Congratulations!

## Install Folder

If you installed your game on your main drive, this should be your installation folder. C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag

# Other Locations
If you installed your game in a different location, follow these instructions to find your installation folder.

1. Open Steam and right-click on Gorilla Tag. Then, go to Manage > Browse local files.
![image](https://user-images.githubusercontent.com/121695210/212397870-f5b1f7a8-b9d5-4789-94cd-91484d21ff37.png)

2. Click the address bar at the top to select your installation folder’s path. Hit CTRL+C to copy this to your clipboard.
![image](https://user-images.githubusercontent.com/121695210/212397961-a5e6a30f-5f35-4a4b-b518-31ee780c8ae1.png)

## Manual Installation
A mod installer is the recommended way to install mods. See the section above. If you have patched the game and just need to install mods that are not available in the installer, skip to step 4.

### Install BepInEx
Download [BepInEx](https://github.com/DeadlyKitten/MonkeModManager/releases/tag/1.3.0)

You will want to get ***BepinEx_x64_VERSION.zip***, with **VERSION** being the version number.

Extract the contents of the BepInEx .zip file to the install folder of your Gorilla Tag installation.
![image](https://user-images.githubusercontent.com/121695210/212398610-98571190-f597-4786-b978-57f5a8b28c39.png)

Run Gorilla Tag once to complete installation.

### Install Mods
Download the mod(s) you wish to install, whether it be from GitHub, the [GorillaTag Modding Discord](https://discord.gg/monkemod) **#pc-mod-releases** channel, or other sources. **Make sure to download any dependencies required by the mod.**
![image](https://user-images.githubusercontent.com/121695210/212398928-9498b734-16b6-49c6-b268-b01113cf89f7.png)

Some mods have installation instructions, some don’t. Generally you can just drag and drop the zip contents into your Gorilla Tag install folder, and the files should go into the corresponding folders. If you have a .dll file, you’ll usually want to put it in BepInEx/plugins.


## Uninstalling Mods
Either remove the mod’s .dll or folder from the BepInEx/plugins folder, which is located in your Gorilla Tag install folder.

## Installing Maps
Check out the [PC Custom Maps Guide](https://gorillatagmodding.burrito.software/#/pc-maploading) for info on custom maps, installation, and where to new new maps.

## Updating Mods
Check out the [PC Mod Updating Guide](https://gorillatagmodding.burrito.software/#/pc-updating) for info on updating Gorilla Tag with mods installed.


# Credits
[Sponsor The Main Writer](https://github.com/sponsors/burritosoftware)
[Tip the Main Writer](https://streamelements.com/burritosoft/tip)
