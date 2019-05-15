# KAwX 

Kerbal Aviator's Weapons Expansion.

A beligerant companion for [KAX](https://github.com/net-lisias-ksp/KAX)!

## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
	+ Delete `<KSP_ROOT>/GameData/KAwX`
* Extract the package's `GameData/KAX` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/KAwX` --> `<KSP_ROOT>/GameData/KAX`
* **Optionally** extract the package's KAX Examples's `Ships` folder into your KSP's as follows:
	+ `<PACKAGE>/Ships` --> `<KSP_ROOT>/Ships`
	+ You may safely overwrite any files as only KAX ships are distributed, and you probably want updated crafts for your game.
* **Selectively** you can extract the `Extras` content into your `GameData` directory. Read below for details. Avoid extracting this if you don't know what you are doing. :)

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[KAwX]
			[Agencies]
				Agents.cfg
				...
			[Localization]
				KAwX__EN-US_localization.cfg
				...
			[Parts]
				...
				[Spaces]
			[Patches]
				...
			[PluginData]
				KAwX_normal.png
				KAwX_selected.png
			[Sounds]
				...
			CHANGE_LOG.md
			KAwX.dll
			KAwX.version
			LICENSE
			NOTICE
			README.md
		ModuleManager.dll
		...
	[Ships]
		[SPH]
			KAX -Peanut.craft
			...
	KSP.log
	PartDatabase.cfg
	...
```

### Extras Content

* Patches : Optional Module Manager patches

### Dependencies

* [KAX](https://github.com/net-lisias-ksp/KAX/releases)
	+ Hard Dependency - parts will not work without it. 
	+ Not Included
* [Firespitter](https://github.com/snjo/Firespitter/releases)
	+ Hard Dependency - parts will not work without it. 
	+ Not Included
* [Module Manager](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*) 3.0.7 or later
	+ Soft dependency - it's possible to play without it, besides having less features available.
	+ Not Included

