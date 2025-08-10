# Central European Keyboard Layout
An alternative QWERTZ keyboard layout for XKB

This is the layout I wrote several years ago, and it has always served me well. I thought it was time to share it with you.

Suitable for polyglots, language freaks, Slavs, slavists, Magyars, Romanians, linguists, and more!

You can write with this layout without switching:
German, English, Hungarian, Polish, Slovak, Czech, Slovene, Croatian, Serbian, Bosnian, Montenegrine, Łacinka, Romanian, Turkish

![xkb-central-european](https://raw.githubusercontent.com/savetier/xkb-central-european/refs/heads/main/xkb-central-european.png)

# Install

Tested on Arch, EndeavourOS, Manjaro, and Ubuntu

The easiest way to install this layout is to to download the file 'ce' and rename it to your standard layout or one you would never use (I renamed it to 'at') and replace this file in the /usr/share/X11/xkb/symbols folder. After that you simply need to add the Austrian (or whichever you have chosen) layout to your keyboard layout profile. 

For example:

	wget https://raw.githubusercontent.com/shape0shift/xkb-central-european/refs/heads/main/ce
	sudo mv ce /usr/share/X11/xkb/symbols/at

(Change 'at' in the end to the one you want to replace)
