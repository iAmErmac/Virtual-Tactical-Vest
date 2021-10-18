# Virtual Tactical Vest for Doom VR

![Virtual Tactical Vest for Doom VR](https://thumbs.gfycat.com/QuaintSlowGermanspitz-size_restricted.gif)

This is an universal addon made to run with vanilla Doom or along with other Doom mods, works in both GZDoomVR and QuestZDoom. You'll see a virtual vest on your virtual body with weapon slots, two holsters on the sides, a chest slot for rifle or shotgun, two hidden slots on two of your shoulders, grenades (if available) on belt and a pack of cigarettes on the chest pocket.

You cannot put fists or cigarette on any weapon slot. Only small arms (Doom weapon slot 2) can be holstered. Rifles and Shotguns (Doom weapon slot 3 and 4) are allowed to put on the chest. Any weapon except the small arms can be stored on your back (two shoulder slots). If there is a weapon available named "Grenade" (but not Grenade Launcher) in the weapon mod you are playing with, it can be grabbed from the grenade slot.

This mod uses the **USE**, **ZOOM** and **USER4** (you can bind a key for it here: **Customize controls > Weapons > Weapon State 4**) keys for VR interactions. Only your main hand can be used to interact with the weapon slots. Move your hand near to a slot to highlight it (make sure to not pointing your weapon directly to the slot or it may not get highlighted). When highlighted an empty slot, Press USE key to put your current weapon in it. Press ZOOM or USER4 button to clear the slot and then you can store another weapon there. Press USE key on a slot with a weapon to grab that particular weapon.

Cigarette can be picked from the cigarette pack on the chest pocket slot. You can throw it to lure enemies on it. They will get agitated by the cigerette butt, will start shooting and may start infighting. When you have health lower than 35 hitpoints you can smoke a cigarette (by moving it closer to your face) to slowly regain health.

To download the Virtual Tactical Vest mod click the download button below:

[![Download Now](https://raster.shields.io/github/downloads/iAmErmac/Virtual-Tactical-Vest/total)](https://github.com/iAmErmac/Virtual-Tactical-Vest/releases/latest)

[<img src="https://cdn.ko-fi.com/cdn/kofi2.png?v=2" height="36" alt="Buy me a Cofee!">](https://ko-fi.com/ermac)

## Features
* 5 tactical vest slots to quickly switch weapons
* 1 Grenade slot (if grenades available as weapon in the mod)
* Visible weapon holsters and stored weapon models (mod will try to use near-matched models)
* Cigarettes to confuse enemies or to smoke and regain health when injured

## Known Issues
* Since the mod uses a hack to locate the main hand controller position, sometimes the controller position data is not found when you point weapon directly to a weapon slot. You should point the weapon away from the weapon slot to highlight it

## Installation

Virtual Tactical Vest mod should work fine with any mod order but it is advised to load it after a weapon mod

### GZDoom VR (PC-VR)

Latest GZDoom VR: https://github.com/hh79/gz3doom/releases

To install:

    Extract GZDoom-VR to a folder.
    Copy original doom wads into the folder.
    Copy this mod into the folder.
    Run with gzdoomvr.exe -iwad doom2.wad -file YOUR_FAVORITE_WEAPON_MOD LATEST_VIRTUAL_VEST_MOD
  
OR use DoomRunner: https://github.com/Youda008/DoomRunner/releases/ to load mods in GZDoom with the right order

### QuestZDoom (Oculus Quest)

Official QuestZDoom: https://github.com/DrBeef/QuestZDoom/releases/latest

QuestZDoom launcher: https://github.com/baggyg/QuestZDoomLauncher/releases/latest

To install:

    Copy this mod into /sdcard/QuestZDoom/mods/
    Load QuestZDoom Launcher. select this mods after a VR weapon mod

## Recommended mods to combine with:

* [Brutal Doom:](https://www.moddb.com/mods/brutal-doom/downloads/brutal-doom-v21-beta)
  - Brutal Doom works very well with this mod having so many weapons to play with. You can get the Brutal Doom VR weapons (made by ajantaju) from [here](https://github.com/ajantaju/br_vr/releases/latest)
  
* [Cola 3: The Soda of Style](https://wildweasel.itch.io/cola-3-the-soda-of-style)
  - A fantastic weapon mod featuring weapon leveling. You can get the Cola VR weapons from [here](https://github.com/iAmErmac/Cola-3-VR-Weapons/releases/latest)

* [Aliens: Eradication](https://www.moddb.com/mods/aliens-eradication-tc)
  - A very almospheric mod about playing as a survivor to fight the Aliens and synthetics. You can get the Aliens VR weapons from [here](https://github.com/iAmErmac/Aliens-Eradication-VR-addon/releases/latest)

* [Doom 64: Retribution](https://www.moddb.com/mods/doom-64-retribution/downloads/doom-64-retribution-version-151)
  - A re-creation of the Original Doom 64 with more polishes. You can get the Doom 64 VR weapons (made by ajantaju) from [here](https://github.com/ajantaju/br_vr/blob/master/D64Retribution.zip)

* [Brutal Doom 64](https://www.moddb.com/mods/brutal-doom-64/downloads/brutal-doom-64-version-10)
  - A re-imagination of the Original Doom 64 with Brutal Doom esque gore and weapons. You can get the Brutal Doom 64 VR weapons (made by ajantaju) from [here](https://github.com/ajantaju/br_vr/releases/download/B35/DooM64_BR_WIP.zip)

* [Brutal Wolfenstein](https://www.moddb.com/mods/brutal-wolfenstein-3d/downloads/zmc-bwfinal)
  - A spinoff of the original Wolfenstein 3D campaign with Brutal Doom esque gore and weapons. You can get the Brutal Wolfenstein VR weapons (made by ajantaju) from [here](https://github.com/ajantaju/br_vr/blob/master/VR_ZMC_BrutalWolf.zip)

* [Robocop Doom](https://mikestoybox.net/2019/03/31/robocop-doom/)
  - Play as Officer Alex Murphy and regain your humanity while seeking revenge against the criminal scum who killed you. You can get the Robocop VR weapons from [here](https://github.com/iAmErmac/Robocop-Doom-VR-Weapons/releases/latest)

## Credits

* All the models for the visual elements are made by Ermac
* ZScript codes for controller tracking and VR interactions are written by Ermac

## 3D Model credits

* Knife model: https://sketchfab.com/3d-models/combat-knife-ab155631f3f24156942da4980f273536
* Machete model: https://sketchfab.com/3d-models/machete-low-poly-b3197e90df2943c1b47dc6bbaa298b72
* Pistol model: https://sketchfab.com/3d-models/berettalowpoly-c4977b72ed3f47b1964f7acd6bd88ce7
* SMG model: https://sketchfab.com/3d-models/low-poly-mp9-f1627581e85749c28a83329c6fb5002d
* Assault Rifle model: https://sketchfab.com/3d-models/m16a1-6c9ab15df350473bb036361c59c953e4
* Shotgun model: https://sketchfab.com/3d-models/shotgun-647e390633004c97893fbf2ccfd3267b
* SuperShotgun model: https://sketchfab.com/3d-models/low-poly-double-barrel-shotgun-9268a86cb1ef470ca5654454fbeea587
* Grenade model: https://sketchfab.com/3d-models/grenade-low-poly-65386b62b82e41b09e277c960ed7439d
* Cigarette Pack model: https://sketchfab.com/3d-models/hero-cigar-60be3ebe1e994c55b2f29c8870bad3b3
* All the weapon models and textures are modified by Ermac
