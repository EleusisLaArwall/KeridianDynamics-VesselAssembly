Keridian Dynamics - Vessel Assembly

Info:
This pack contains a Furnace and a ChemicalReactor to convert Ore to Metal and a 3D-Printer to print RocketParts from Metal. Also some launchpads that require ExtraplanetaryLaunchpads to assemble vessels from Rocketparts and some tanks to store Metal and RocketParts. The production-chain is very basic: Ore --> Metal --> RocketParts --> Vessel.

Installation:
1. Make backups of your save-files and/or customised configs.
2. Delete older versions of Keridian Dynamics - Vessel Assembly.
3. Copy the 'GameData' folder inside the zip file to your Kerbal Space Program directory.

Dependency (100% required):
-ModuleManager
-ResourceSwitch (InterstellarFuelSwitch OR Firespitter OR B9PartSwitch)

Dependency (99.9...% required. KSP will load all parts but some will have reduced or no function):
-ExtraplanetaryLaunchpads OR SimpleConstruction (without this the Laucnhpads, Launchsite, Sledgehammer, MobileVAB, OrbitalHangar will have no function)
-Kerbal Inventory System (without this the Launchsite and Sledgehammer will have no function)
-Kerbal Attachment System (without this the RecycleSite will dump all recycled resources)
-JSI Advanced Transparent Pods (without this the passable and nonpassable Storage Tanks will have no IVA overlay)
-PatchManager (without this the MM patches are not toggleable)
Note: The config autodetects if Firespitter or InterstellarFuelSwitch or B9PartSwitch is installed and uses the corresponding modules. If multiple ResourceSwitchers are installed, the priority goes as follows: IFS > FS > B9PS 

Recommended/supported Mods:
-OSE Workshop (highly recommended)
-GTIndustries (highly recommended)
-CommunityTechTree (config included)
-AVC
-Community Resource Pack
-Connected Living Space

ExperimentalSection:
WARNING: Very WIP! May not function as advertised. Designed for testing.
Installation: Copy the 'GameData' folder from ".zip/WIP_ExperimentalSection" to your Kerbal Space Program directory and overwrite if asked.
The textures are complete overkill atm. Included lower-res textures (untested).

Warranty:
The Mod is in development, so no warranty if it breaks craft- or save-files. Make backups in time!

License:
CC-BY-SA 4.0 International 
https://creativecommons.org/licenses/by-sa/4.0/legalcode

Changelog:
2018.04.15 - The No-Title-Pre-Release Update - v0.8.9
	- Compatibility to EL 6.0
	- Re-export all models (except Internals) with unity 2017.1.3p1 and latest parttools
	- Language support (english)
	- B9PartSwitch support
	- A Resource-Switcher (FS, IFS or B9PS) is now mandatory
	- All Resource Converters are enabled by default (some require CRP)
	- Patchmanager support
		- Ore->Metal converters can be disabled
		- MetalOre->Metal converters can be disabled
		- ScrapMetal->Metal converters can be disabled
		- Metal->RocketParts converters can be disabled
		- Metal->MaterialKits converters can be disabled
		- Metal+Ore->SpecializedParts converters can be disabled
		- Dirt->RareMetals+ExoticMinerals converters can be disabled
		- Old costs can be restored
		- Station Tank Series can be disabled
		- (Cargo) Tank Series can be disabled
		- Station Tank Series can be crewed
		- OSE Workshop default Resource can be switched from MaterialKits to RocketParts
	- Integrated 534443s cost-rebalance (thanks a lot!)
	- Reintegrated Station Tank Series
	- Fixed unused switcher for Cargo Tanks
	- StockDrill Patch only applies if no other MetalOre harvester is present already
	- Added MetalOre Harvester to MiniDrill
	- Reworked Spawn Markers
	- Redo MetalOre converters (density change 0.0275->0.026)
	- Removed very old hexagonal tanks used when FS and IFS are not installed (no replacement)
	- Removed KD-OrbitalPad, KD-SidePad and KD-TopPad
	- New Parts:
		- KD-Keronica: Rework of the old OrbitalPad. Advanced Probe Core with Launchpad.
		- KD-LaunchPad (2 Variants 1.25,2.5): Light-weight replacement for OrbitalPad
		- KD-LaunchPadSide (2 Variants 1.25,2.5): Light-weight replacement for SidePad
		- KD-LaunchPadTop (2 Variants 1.25,2.5): Light-weight replacement for TopPad
		- KD-ExtensionPad (6 variants, 0.625-5.0 meters): Light-weight part to extend exisiting vessels (ELDisposablePad)
		- KD-FAVA (early prototype): Fully Automated Vessel Assembler. generates productivity without the need for Kerbals

2017.01.21 - Recycling Everything - v0.8.2
	-Moved parts to customisation: KD-STXXXXFS. New Adapters included.
	-New part: KD-FurnaceSmall.
	-New part: KD-FabricationContainer (Metal --> Rocketparts; needs an engineer).
	-New part: KD-PAM (Planetary Assembly Management aka SurveyStation); has no IVA currently.
	-New part: KD-PAMSmall.
	-New part: KD-RecyclerSmall.
	-New part: KD-RecycleSite (Needs KAS).
	-New parts: KD-T125XFS (X=variant) 1.25 m Storage Tanks in 3 sizes(1, 2, 4 m)).
	-New part: KD-T2001FS (1.25 to 2.5 m storage adapter).
	-Re-exported most of the models with improved shading and materials.
	-Re-worked most of the animations. Except the tanks all parts use ModuleColorChange for glow animations (can be changed in cfg).
	-Overhauled resource storage and mass for ALL tanks.
	-Added ScrapMetal setup.
	-Added LFO setup (temporary, for balancing. Will be replaced in the future).
	-Added surface attach to some parts (Launchpads for example).
	-Fixed Furnaces MetalOre extraction ratio. Now really 70% (was 100 before).
	-Recycling produces ScrapMetal and small amounts of Metal.
	-Added ScrapMetal-->Metal converters (Furnaces,ChemicalReactor).
	-Changed SpecialistBonus for KD-Furnace.
	-Changed SpecialistBonus for KD-3D-Printer.
	-ChemicalReactor can now extract RareMetals and ExoticMinerals from Dirt (if OSE Workshop is installed).
	-Changed dependency for Metal,Ore-->SpecializedParts converter to require UmbraSpaceIndustries.
	-Changed SimpleConstruction support: If SC is installed the following changes are applied:
		1. No MetalOre Harvester.
		2. No MetalOre-->Metal converters.
		3. Ore-->Metal converters give 70 times more Metal.
		4. Metal tanks storage-capacity is increased by factor 5 (ingame units, not mass!).
	-Changed FS/IFS priority. If both are installed IFS module will be used.
	-Added optional config to use RocketParts with OSE Workshop instead of MaterialKits, RareMetals & ExoticMinerals (KeridianDynamics-OSE-RP.cfg).

2016-11-28 - Balancing update one - v0.8.1
	-New part: KD-ChemicalReactor (Ore --> Metal+LFO)
	-New parts: KD-T250XFS (X=variant) 2.5 m non-passable Storage Tanks in 3 sizes (1, 2, 3 m).
	-New parts: KD-T375XFS (X=variant) 3.75 m non-passable Storage Tanks in 3 sizes (1, 3, 6 m).
	-New part: KD-T3252FS 3.75 m to 2.5 m non-passable Storage Tank adapter (2 m).
	-Removed parts: KD-T125FS and KD-T250FS.
	-Increased Furnace conversion speed (~15 times faster, extr.-rate remains 1%-mass).
	-Added MetalOre --> Metal converter to Furnace by default (~70%-mass extr.-rate).
	-Added MetalOre harvester to Stock drill (Big one only).
	-Increased 3D-Printer conversion speed (~21 times faster, conv.-rate remains 100%-mass).
	-Reduced 3D-Printer mass to 1.85 tons.
	-Included compatibility patch for SimpleConstruction.
	-Updated converter specialty to ExperienceEffect (3D Printer,Furnace = ConverterSkill; ChemicalReactor = ScienceSkill).
	-Added Bulkheadprofiles.
	-Added tags.
	-Added ScienceExperiment: OreScience to Stock Drill (Big one only).

2016-07-06 - Storage update - v0.8
	-New part: KD-OrbitalHangar. Big Launchpad for orbital construction and other stuff.
	-New parts: KD-ST250XFS (X=variant) 2.5 m crew-passable Storage Tanks in 3 sizes (1, 2, 3 m).
	-New parts: KD-ST375XFS (X=variant) 3.75 m crew-passable Storage Tanks in 3 sizes (1, 3, 6 m).
	-New part: KD-ST3252FS 3.75 m to 2.5 m crew-passable Storage Tank adapter (2 m).
	-Community Resource Pack now triggers storage configurations for MaterialKits,... (instead of OSE because CRP is bundled with OSE).
	-Added JSI Advanced Transparant Pods dependency.
	-Added support for ConnectedLivingSpace.
	-Added optional config that allows the 3D-Printer to make MaterialKits from Metal in customisation.
	-KD-MobileVAB: Minor model tweaks. Airlock moved to the bottom; Fixed IVA light.
	-LaunchSite: One arm glows in a darker blue now.
	-Launchpads and MobileVAB have proper names for EL GUI.
	-All parts have been rebalanced in cost, cost to unlock and tech-node (Stock and CTT).
	-Changed capacity for MaterialKits, RareMetals, ExoticMinerals and Monoprop. on old tanks.

2016-05-16 - Universal Assembly - v0.7
	-New part: KD-MobileVAB. Acts primary as Survey Station and offers a high productivity factor for up to 12 Kerbals.
	-New part (previously experimental): KD-LaunchSite (reworked). Acts as Survey Stake.
	-New part (previously experimental): KD-SledgeHammer. Needed to attach the LaunchSite to the ground.
	-All parts above need Kerbal Inventory System to work properly.
	-Added support for OSE workshop.
	-KD-3D-Printer can convert Ore to MaterialKits.
	-KD-MobileVAB can be used as OSE workshop and OSE recycler.
	-KD-T125FS and KD-T250FS have 2 additional setups (Materialkits and RareMetals/ExoticMinerals).
	-InterstellarFuelSwitch is not a dependency anymore but still supported and highly recommended.
	-Added support for Firespitter (FSmeshSwitch & FSfuelSwitch).
	-Added MM-config that autodetects if Firespitter and/or InterstellarFuelSwitch is installed and applies the corresponding modules to the tanks. (If both are NOT installed, two tanks for RocketParts and two tanks for Metal are available)

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
	
A very big THANK YOU to the following mod developers and specially the plugin-writers/maintainers (because that is witchcraft to me ;) ) for their hard work:
taniwha and skykooler for ExtraplanetaryLaunchpads.
sarbian for ModuleManager.
cybutek for KSP-AVC.
FreeThinker for Interstellar Fuel Switch.
KospY, Winn75 and Igorz for Kerbal Inventory System.
ObiVanDamme and Enceos for OSE Workshop.
Snjo and RoverDude for Firespitter.
RoverDude for Community Resource Pack.
JPLRepo for JSI Advanced Transparant Pods.
Codepoet and Papa_Joe for Connected Living Spaces.
linuxgururgamer for PatchManager.
Warezcrawler for GTIndustries.

Also I'd like to give a big THANK YOU for the Mod Development Links Compilation and modding tutorials on the KSP forum to Cpt. Kipard and everyone who contributed. 

Thanks to everyone who gives or ever gave feedback! It's very important for me and highly appreciated.
Special thanks:
Sigma88 for the ModuleManager-configs and support! (Check out his awesome stuff here if you haven't already).
wasml for the Recycler suggestion.
colmo for the Fundament suggestion.
DaniDE for the name-suggestions and the translation of the company Motto - PECUNIA PER KERBULUS 
Joshwoo70 / Joshwoo69 for the OrbitalHangar suggestion.
Dr Farnsworth for continued feedback, testing and a lot of very helpfull suggestions.
534443 for the cost and entryCost rebalance