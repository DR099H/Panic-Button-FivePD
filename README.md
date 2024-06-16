# Panic Button FivePD
Customizable Panic Button for FivePD

# About
The plugin is written in C# and consists of a FiveM resource and a FivePD plugin

Plugin creates a [blip](https://github.com/DR099H/panic-button-fivepd/assets/147756922/c1091a76-e577-43c1-9669-edee7ad79908) on the map and plays panic sound

Prints player's name who activated panic:

![image](https://github.com/DR099H/panic-button-fivepd/assets/147756922/7ee74345-b9cd-44c3-b77f-f231d9dda3fd)


You can't use button while you are off duty

When you sit in car, plugin routes you to place where button is activated

In default, you have 2.5 minutes of panic sound and 5 minutes of blip life (*or you can off it when you want*)

### Commands

`/pb` to activate button, `/pboff` to deactivate it

Plugin has a config file where you can **customize**:
---
- **Compatibility with CC RP Chat**
- **Delay** (*depends on sound file lenght*)
- **Number of Repeats** - more info in config
- **Volume** of Panic sound
- **Blip Life** duration
- **Translation** of all chat and suggestions text
- ...*any suggestions?*

# Installation
- Download the [latest release](https://github.com/DR099H/panic-button-fivepd/releases/latest) of Panic Button
- Simply drag-n-drop archive contents in your resource folder

**DON'T RENAME RESOURCE, please** :)

### For FivePD
You'll need to add one line in `fxmanifest.lua`:

- Add `'./SharpConfig.dll',` in the `files` section of manifest

### Make sound work
Plugin uses [PlayCustomSounds](https://github.com/LondonStudios/PlayCustomSounds) to play sound, so you need to install it

## I think we've done!
It's my first release, don't judge ;)
