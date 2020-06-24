# Emulatrix

Multiplatform Emulator - Sega Genesis, Nintendo, Super Nintendo, GameBoy, GameBoy Color, GameBoy Advance, MAME32, DOSBox and Virtual Machines.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Emulatrix/master/Emulatrix.png)

## Web version

https://www.emulatrix.net

## Android version

https://play.google.com/store/apps/details?id=net.emulatrix

## IMPORTANT - After selecting the upload icon

| PLATFORM  | HOW TO PLAY A GAME?  | FILE FORMAT | NOTE |
| :------------ |:---------------:| :-----:| :-----:|
| Nintendo | Select the game file from your hard drive. | NES | --- | 
| Super Nintendo | Select the game file from your hard drive. | SMC, SFC, SRM | --- |
| GameBoy | Select the game file from your hard drive. | GB | --- |
| GameBoy Color | Select the game file from your hard drive. | GBC | --- |
| GameBoy Advance | Select the game file from your hard drive. | GBA | --- |
| Sega Genesis | Select the game file from your hard drive. | BIN, SMD, MD | --- |
| MAME32 | Select the game file from your hard drive. | ZIP | Do not rename the ZIP file. |
| DOS | Select the game file from your hard drive. | ZIP | Will try to run AUTORUN.BAT |
| Virtual Machines | Select the disk file from your hard drive. | ZIP | Must contain a c.img file.<br/>It will be mounted and booted. |

## DOSBox useful commands

| TYPE IN THE PROMPT  | RESULT  |
| :------------ |:---------------:|
| config -set "cycles=4000" | Default emulation speed |
| config -set "cycles=10000" | Faster emulation speed |
| config -set "cycles=15000" | Faster emulation speed |
| config -set "cycles=20000" | Fastest emulation speed |
| config -set "sbtype=none" | Sound Blaster disabled |

## Original core files

| PLATFORM  | URL  | CORE | VERSION
| :------------ |:---------------:| :-----:| :-----:|
| Nintendo | https://buildbot.libretro.com/stable | fceumm | 1.8.2
| Super Nintendo | https://buildbot.libretro.com/stable | snes9x2010 | 1.8.2
| GameBoy | https://buildbot.libretro.com/stable | gambatte | 1.8.2
| GameBoy Color | https://buildbot.libretro.com/stable | gambatte | 1.8.2
| GameBoy Advance | https://buildbot.libretro.com/stable | vba_next | 1.8.2
| Sega Genesis | https://buildbot.libretro.com/stable | genesis_plus_gx | 1.8.2
| MAME32 | https://buildbot.libretro.com/stable | fbalpha2012 | 1.8.2
| DOS | https://github.com/dreamlayers/em-dosbox | dosbox | -

## Core files modifications

| PLATFORM  | TYPE  | DETAILS |
| :------------ |:--------------- |:---------------|
| Nintendo | Bugfix | Delayed compilation workaround |
| Nintendo | Bugfix | Content resized to canvas |
| Nintendo | Feature | Load/save state implementation |
| Super Nintendo | Bugfix | Delayed compilation workaround |
| Super Nintendo | Bugfix | Content resized to canvas |
| Super Nintendo | Feature | Load/save state implementation |
| GameBoy | Bugfix | Delayed compilation workaround |
| GameBoy | Bugfix | Content resized to canvas |
| GameBoy | Feature | Load/save state implementation |
| GameBoy Color | Bugfix | Delayed compilation workaround |
| GameBoy Color | Bugfix | Content resized to canvas |
| GameBoy Color | Feature | Load/save state implementation |
| GameBoy Advance | Bugfix | Delayed compilation workaround |
| GameBoy Advance | Bugfix | Content resized to canvas |
| GameBoy Advance | Feature | Load/save state implementation |
| Sega Genesis | Bugfix | Delayed compilation workaround |
| Sega Genesis | Bugfix | Content resized to canvas |
| Sega Genesis | Feature | Load/save state implementation |
| MAME32 | Bugfix | Delayed compilation workaround |
| MAME32 | Bugfix | Content resized to canvas |
| MAME32 | Feature | Load/save state implementation |
| DOS | Bugfix | Launching emulator on blur |
| DOS | Bugfix | Paused/resumed emulation on blur/focus |
| DOS | Feature | Load/save file implementation |

## Virtual joystick code

https://github.com/lrusso/VirtualJoystick
