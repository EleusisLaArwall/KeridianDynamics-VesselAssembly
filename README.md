Keridian Dynamics - Vessel Assembly

Info:
This pack contains a Furnace to convert Ore to Metal and a 3D-Printer to print RocketParts from Metal. Also some launchpads that require ExtraplanetaryLaunchpads to assemble vessels from Rocketparts and some tanks to store Metal and RocketParts. The production-chain is very basic: Ore --> Metal --> RocketParts --> Vessel.

Installation:
1. Make backups of your save-files and/or customised configs.
2. Delete older versions of Keridian Dynamics - Vessel Assembly.
3. Copy the 'GameData' folder inside the zip file to your Kerbal Space Program directory.

Dependency:
-ModuleManager
-ExtraplanetaryLaunchpads
-InterstellarFuelSwitch
Note: KSP will load all parts but without ModuleManager and ExtraplanetaryLaunchpads the Laucnhpads will have no function. The resource-config from Customisation is required for this scenario.

Customisation:
-This folder contains resource-definitions that are required if you don't have ExtraplanetaryLaunchpads installed. 
-The ModuleManager-patches change the input-resource of the Furnace from Ore to MetalOre or MetallicOre (Extract-ratio = 0.7017 = [3*m(Fe)+4*m(O)]/[3*m(Fe)] for Fe3O4; 1kg M.Ore --> 0.7kg Metal). 
-To install one of the customisations above copy the .cfg-file somewhere in the GameData-folder.
-To reduce RAM-usage copy the .dds files from ".zip/Customisation/512x512textures" into the corresponding folder inside "GameData/KeridianDynamics/Parts/".

ExperimentalSection:
WARNING: Very WIP! May not function as advertised. Designed for testing.
Dependency: Kerbal Inventory System
Installation: Copy the 'GameData' folder from ".zip/WIP_ExperimentalSection" to your Kerbal Space Program directory and overwrite if asked.
The textures are complete overkill atm. Included lower-res textures (untested).

Supported Mods:
-CommunityTechTree (config included).
-AVC

Warranty:
The Mod is in development, so no warranty if it breaks craft- or save-files. Make backups in time!

License:
CC-BY-SA 4.0 International 
https://creativecommons.org/licenses/by-sa/4.0/legalcode

Changelog:
2016-05-01 - PECUNIA PER KERBULUS - v0.6.1
	-Reexported models with Unity 5 and PartTools 1.1.
	-New Company Motto: PECUNIA PER KERBULUS. (Thanks to DaniDE for translation!)
	-Reworked Logo and Flags.
	-Used "Icon_Hidden" tag. (Thanks to Badsector for the hint!)
	-Added ExperimentalSection (needs KIS).
	-New experimental part: KD-Fundament. (Thanks to colmo for the suggestion!)
	-New experimental part: KD-LaunchSite.
	-New experimental part: KD-SledgeHammer "Susie".

2016-04-16 - Recycling - v0.6
	-Added Interstellar Fuel Switch dependency. (Tank names have changed, be careful with savegames!)
	-Reworked models. (Colliders have not changed.)
	-Added Normal maps.
	-Added Emissive maps.
	-Added new animations.
	-Reworked Furnace behavior. No more seperate heating needed. 
	-Furnace needs much less EC but produces more heat.
	-New part: KD-Recycler. (Roll-animation and ExRecycler need to be activated seperately)
	-Updated CTT-compatibility.

2016-02-27 - 2016 update - v0.5
	-Reworked tanks. (Names have changed, so be carefull with savegames!)
	-Changed RoverPads to TopPad and SidePad. (Names have changed, so be carefull with savegames!)
	-New mesh-colliders for all parts (be carefull with savegames!).
	-Toggleable Spawn Marker for all Pads added. A vessel from SPH will point in the direction of the arrowtip. VAB vessels will still point upwards.
	-KD-OrbitalPad, KD-SidePad, KD-TopPad and all tanks now share the same texture (KD-OrbitalPad.dds).
	-Added thermal properties to KD-Pad and KD-OrbitalPad to prevent overheating-explosions during vessel-launch (might be exploitable ...).
	-Added thermal curves to KD-Furnace and KD-3D-Printer.
	-The Furnace needs to heat up before Metal can be extracted. CoreTemperature must at least reach 1800 K to start the extraction! Heating needs a lot of ElectricCharge. Once the extraction has started the heater can be turned off. 
	-The 3D-Printer needs 20 ElectricCharge instead of 10. It needs RoomTemperature to operate (300 K). Heat production is rather low.
	-Some minor model and texture changes.
	-Added 512x512 textures to Customisation.
	-Added "KD-Example Craft.craft" to Customisation.
	-Updated CTT-compatibility.

2015-08-23 - License update - v0.4
	-License changed to CC-BY-SA 4.0 International
	-New experimental parts: KD-RoverPad & KD-RoverPad2
	-KD-Furnace: CoM -0.1 down
	-KD-Pad: CoM -0.87 down
	-KD-OrbitalPad: CoM -0.47 down
	-Moved MM-patches for EL into one config. (Delete old versions before updating!)

2015-08-10 - Orbital Assembly - v0.3
	-New part:	- KD-OrbitalPad
	-KD-Pad fixes: 	- Now transparent in Editor when not attached.
			- Model and texture refined.
			- Center of mass adjusted.
	-KD-3D-Printer:	- Model and texture refined (a little).
	-Added support for AVC.

2015-08-03 - Hotfix - v0.2
	-Fixed MM-config for MetalOreFurnace and MetallicOreFurnace.
	-Reconverted textures to DDS.

2015-07-27 - Initial Release - v0.1
	-New part: KD-Furnace
	-New part: KD-3D-Printer
	-New part: KD-Pad
	-New part: KD-TankHex1-Metal
	-New part: KD-TankHex1-RocketParts
	-New part: KD-TankHex2-Metal
	-New part: KD-TankHex2-RocketParts