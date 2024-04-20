Gamepad to keyboard, buttons and analogue inputs remapping. Detailed options with auto-repeat and re-scaling. MCM SkyUI interface provided. 

Description

Modkeys and hotkeys for gamepad buttons using Xinput with in-game configuration.
This plugin does not alter any existing gamepad or keyboard configuration that the game provides. All settings are made independently. They can be turned on or off individually, at any point; or completely by deinstalling the plugin.

With Xinput Modkey SE one or any simultaneously pressed number of gamepad buttons can be assigned into:

    another gamepad button or buttons,
    keyboard key or keys,
    mouse button or
    combination of the above.


Features:

    Configurable auto-repeat, aka. turbo function.
    Choose whenever to suppress selected inputs while simulating others.
    Can simulate keys that doesn't exist on your physical keyboard.
    Rescale analogue inputs by holding a button. Eg. can be used for walk mode with any chosen speed.


Not much to say otherwise. Try browsing through its in-game settings to see details.


Installation

Install with mod manager (eg. NMM or MO2). Correct archive content structure provided.
Make sure to download Mod version compatible with your game version, eg. v1.5.73.
After installation and loading the game save, wait for the SkyUI MCM message telling that new menu entry has been registeted - an entry of this Mod.


Uninstall

If you would like to backup your settings then the INI file is stored under this location:
./Data/SKSE/Plugins/XinputModkeySeMcmByIkk.ini


Troubleshooting

Please see first post in the Posts section.


Project Information

This project Is using Papyrus scriptsing, SKSE and SkyUI functions. Internally, Xinput is used to filter gamepad buttons and tp generate new inputs. Open source project. Source code available in the download section.

Summary of software used, that is not Skyrim related:

    Xinput - part of Windows SDK by Microsoft
    Detours - software package by Microsoft (website﻿)


This project is build using Microsoft Visual Studio 2017 C++ compiler. Only compiler is used and not IDE. Compiler configuration used should be quite standard, but if it's required to know all the options, then the project configuration can be obtained from "project.cbp" file, configuration for Code:Blocks IDE.

If you would like to use it with some other game, not only Skyrim SE, then you can try my other project called Xinput Modkey that can be found here﻿.


Credits

    Bethesda for Skyrim and Fallout games (page﻿).
    SKSE developers (page)
    Detours library for Windows (page)
    SkyUI (page)
    Thanks to olegbl for info on update to the AE version.
    Thanks to QuietPippin for compatibility info and testing.

