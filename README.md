# improved-osk-gnome-ext

Makes Gnome's onscreen keyboard more useable.

Features:
* More buttons like CTRL, F-Keys, Arrow Keys...
* Resize desktop on popup
* Configurable keyboard size (landscape/portrait)
* Toggle auto keyboard popup on touch input 
* Works in gnome password modals
* Statusbar indicator to toggle keyboard

This extension is a fork of [luebke-dev/gnome-shell-extension-improve-osk](https://github.com/luebke-dev/gnome-shell-extension-improve-osk). 

## Installation

1. Clone the git repo 
```console
git clone https://github.com/mateusz-kamyk/improved-osk-gnome-ext.git ~/.local/share/gnome-shell/extensions/improvedosk@mkamyk.io
```
2. Enable extension
```console
gnome-extensions enable improvedosk@mkamyk.io
```
3. Reload gnome or reboot system

## FAQ

### Some symbols are missing...
the keyboard uses unicode characters, try install ttf-symbola on archlinux (AUR) or ttf-ancient-fonts-symbola on ubuntu/debian

### Do i need to enable the OSK in Gnome accessibility settings?
By default the keyboard will popup on touch input events. Enabling the keyboard in the accessibility settings just allows the OSK to popup on non touch input.
