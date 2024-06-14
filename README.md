# panic-button-fivepd
Customizable Panic Button Addon for FivePD

# About
The plugin is written in C# and consists of a FiveM resource and a FivePD plugin

Plugin creates a [blip](https://github.com/DR099H/panic-button-fivepd/assets/147756922/c1091a76-e577-43c1-9669-edee7ad79908) on the map and plays panic sound

It prints messages in chat, so you can find out who activated the button

When you sit in car, plugin routes you to place where button is activated

In default, you have 2.5 minutes of panic sound and 5 minutes of blip life (*or you can off it when you want*)

`/pb` to activate button, `/pboff` to deactivate it

Plugin has a config file where you can **customize**:
---
- **Compatibility with CC RP Chat**
- **Delay** of your sound file
- **Volume** of Panic sound
- **Translate** all chat and suggestions text
- ...

# Installation
Simple drag-n-drop archive contents in your resource folder

**DON'T RENAME RESOURCE, please** :)

### For FivePD
You'll need to add one line in `fxmanifest.lua`:

- Add `'./SharpConfig.dll',` in the `files` section of manifest

### Make sound work
Plugin uses [PlayCustomSounds](https://github.com/LondonStudios/PlayCustomSounds) to play sound, so you need to install it

**Next step**
- Put the sound in `resources/PlayCustomSounds/html/sounds/`

## I think we've done!
It's my first release, don't judge ;)
