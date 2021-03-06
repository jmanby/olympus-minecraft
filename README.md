Olympus Mod Pack for Minecraft
==============================
This is a mod pack that is run on a private, whitelisted Minecraft server. It is provided here for ease of access for its members, with the side benefit of allowing any interested parties to host servers of their own using this mod pack. I hope that it will be enjoyed by both visitors and members alike! If you plan to redistribute this mod pack, however, please be sure to comply with all the wishes of each mod's author regarding redistribution, just as I have. Installation instructions, a list of included mods, and proper credits for all mod developers can be found here.

## Installation
This mod pack is designed to be run using MultiMC, an excellent tool for managing multiple versions of Minecraft. If you do not have MultiMC, you can download it [here](http://multimc.org/). You also need to have a git shell installed. For Windows, I recommend installing [msysgit](http://msysgit.github.io/).  

*When installing git on Windows, remember to enable usage on the Windows command prompt! This is necessary for the update script `update.bat` to function correctly. To start a git shell on Windows, right-click in Windows Explorer or on your desktop and select "Git Bash" from the menu.*

#### MultiMC (recommended)
TL:DR - Clone this repo into your MultiMC instances folder. Yes, That's it.

*These instructions assume a default installation of MultiMC, so step 2 will change based on where MultiMC is actually installed. This applies to both installation and update procedures.*

1. Start a git shell
2. `cd ~/MultiMC/instances`
3. `git clone https://github.com/faceles-saint/olympus-minecraft`
4. In MultiMC, click the green icon to reload your instance list
5. Select the new instance and click "Play" to launch Minecraft

#### Updates
If you installed this mod pack using the MuliMC instructions, updates are a simple matter of pulling any changes down from the repository on GitHub.

_Windows_
  1. Open the Olympus Modpack instance folder (click "Instance Folder" in MultiMC)
  2. Run `update.bat`

_Universal_
  1. Start a git shell
  2. `cd ~/MultiMC/instances/olympus-minecraft`
  3. `git fetch origin master && git reset --hard FETCH_HEAD`

#### Minecraft
While this mod pack will certainly run using the official Minecraft launcher, you really should just download MultiMC. If you insist on installing this way, you are on your own. Updates will also have to be performed manually if you don't use MultiMC.

1. Create a new profile using Minecraft version 1.7.10
2. Run Minecraft using this profile at least once
3. Run the Forge installer (located in the "server" folder) and follow its instructions
4. Copy the 'mods' and 'config' folders into your minecraft folder
5. Lauch Minecraft using the "Forge" profile to use the mod pack

*After installation, the 1.7.10 profile created in step 1 can be deleted.*

## Mod Pack Information
#### Version Information
| Mod pack:      | 2.1.0
|----------------|-----------------|
| Minecraft      | 1.7.10   
| Forge          | 10.13.0.1208
| Liteloader     | 1.2.10-03

#### Mods
|       Client Mods       |        Version        |  Author  |
|-------------------------|-----------------------|:--------:|
| Back Tools              | 4.0.0                 |[iChun](http://ichun.us/mods/back-tools/)
| Damage Indicators       | 3.2.0                 | [Rich1051414](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286538)
| iChunUtil               | 4.0.0                 | [iChun](http://ichun.us/mods/ichunutil/)
| VoxelMap                | 1.2.3                 | [MamiyaOratu](http://www.mediafire.com/download/mx5hsfyi6l04kj4/mod_voxelMap_1.2.3_for_1.7.10.litemod)

|       Server Mods       |        Version        |  Author  |
|-------------------------|-----------------------|:--------:|
| Advanced Solar Panels   | 3.5.1                 | [SeNtiMeL](http://forum.industrial-craft.net/index.php?page=Thread&threadID=3291)
| Applied Energistics     | 2-rv1-stable-10       | [AlgorithmX2](http://ae2.ae-mod.info)
| Backpacks               | 2.0.0                 | [Eydamos](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286124)
| BiblioCraft             | v1.8.1                | [Joseph "Nuchaz" Sinclair](http://www.bibliocraftmod.com/)
| BiblioWoods             | 1.7                   | [Joseph "Nuchaz" Sinclair](http://www.bibliocraftmod.com/?page_id=50)
| Biomes O' Plenty        | 2.1.0.978             | [Glitchfiend](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286162)
| Blood Magic             | v1.1.0                | [WayofTIme](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1290532)
| Botania                 | r1.2-116              | [Vazkii](http://vazkii.us/mod/Botania/index.php)
| Buildcraft              | 6.0.18                | [SpaceToad](http://www.mod-buildcraft.com/)
| Carpenter's Blocks      | v3.2.6                | [Mineshopper](http://www.carpentersblocks.com/)
| Chisel                  | 1.5.6b                | [Automatic Maiden](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1288400)
| Code Chicken Core       | 1.0.3.23              | [Chickenbones](http://www.chickenbones.craftsaddle.org/Pages/links.html)
| CoFH Core               | 3.0.0B6-32            | [TeamCoFH](http://teamcofh.com/)
| Dimensional Anchors     | 59.0.2                | [immibis](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
| EnderIO                 | 2.0.1.194             | [CrazyPants](http://enderio.com/)
| Ender Storage           | 1.4.5.21              | [Chickenbones](http://www.chickenbones.craftsaddle.org/Pages/links.html)
| Forbidden Magic         | 0.51                  | [SpitefulFox](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1445828)
| Glowstone Wire          | 1.0.2.113             | [GrygrFlzr](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1280347)
| Immibis Core            | 59.0.3                | [immibis](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1281065)
| Industrialcraft         | 2.2.624-experimental  | [IC2 Dev Team](http://forum.industrial-craft.net/index.php?page=Thread&threadID=9843)
| Inventory Tweaks        | 1.59-dev-152          | [Kobata](http://inventory-tweaks.readthedocs.org/en/latest/)
| Iron Chests             | 6.0.51.734            | [cpw](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1280827)
| Jabba                   | 1.1.4                 | [ProfMobius](http://minecraft.curseforge.com/mc-mods/73510)
| Mantle                  | 0.3.0                 | [mDiyo](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287648)
| Mekanism                | 7.1.0.92              | [aidancbrady](http://aidancbrady.com/mekanism/)
| NEI Plugins Unofficial  | 1.1.0.8               | [Tonius](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1294687)
| Nether Ores             | 2.3.0RC3-84           | [Skyboy026](http://minecraft.curseforge.com/mc-mods/66675)
| Not Enough Items        | 1.0.3-51              | [Chickenbones](http://www.chickenbones.craftsaddle.org/Pages/links.html)
| Open Components         | 0.2.0.17              | [Sangar](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1293018)
| Open Computers          | 1.3.4.63              | [Sangar](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1293018)
| Project Red             | 4.4.9.48              | [MrTJP & Chickenbones](http://projectredwiki.com/wiki/Main_Page)
| SG Craft                | 1.3.3                 | [Greg Ewing](http://www.cosc.canterbury.ac.nz/greg.ewing/minecraft/mods/SGCraft/)
| Tinkers' Construct      | 1.6.0d39              | [mDiyo](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1287648)
| Thaumcraft              | 4.2.0.1               | [Azanor](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292130)
| Thaumic Exploration     | 1.17                  | [Flaxbeard](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/1445786)
| Thaumic Tinkerer        | 2.5-155               | [Pixlepix](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289299)
| Thermal Expansion       | 4.0.0B5-13            | [TeamCoFH](http://teamcofh.com/)
| Thermal Foundation      | 1.0.0B3-8             | [TeamCoFH](http://teamcofh.com/)
| Translocator            | 1.1.1.9               | [Chickenbones](http://www.chickenbones.craftsaddle.org/Pages/links.html)
| Twilight Forest         | 2.2.3                 | [Benimatic](http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1276258)
| Waila                   | 1.5.3                 | [ProfMobius](http://minecraft.curseforge.com/mc-mods/73488)

## Credits
#### Minecraft
Minecraft is the property of Mojang AB, and the server for this mod pack is operating in full compliance with their EULA. The Minecraft client is not included in this mod pack and must be purchased separately.

#### Mod Developers
Great care has been taken with every single mod to ensure that this mod pack is in full compliance with all copyright licenses and provides proper credit to each mod's developer(s) as listed above, along with links to their websites or Minecraft forum pages.
