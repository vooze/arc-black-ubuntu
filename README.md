# Arc Black Ubuntu

This is my attempt at making the arc-theme at bit more unity-friendly, with (in my opinon) better colors.

Theme now supports xfce, thanks to https://github.com/Benoth. - Please open an issue, if you find some bugs.

This theme is build with GTK2 GTK3.18 in mind, so it's for xubuntu + ubuntu unity 16.04 ONLY. - If you dont like OSX icons,  you  can use the orignals with theme noOSX.

Theme is a fork of https://github.com/horst3180/arc-theme/ - Thanks to horst3180 for his wonderful theme.

If you have more suggestions feel free to ask or make pull-requests.

You will need to install gnome-themes-standard & gtk2-engines-murrine to make sure everything works.

## Changes made

- Changed from blue to black (#2f2f2f)
- Made text white insted of gray-ish.
- Made default text darker, so it's easier to read.
- Changed nautilus + GtkFileChooserDialog to have a less dark sidebar.
- Made two versions, with and without OSX buttons.
- Disabled transparency
- Made the unity top bar the same color as other windows.
- Deleted all non-unity stuff
- Made menus black/white instead of white/black, which made some problems for the unity top bar - icons would not show in the correct color. - White icons on white background is ugly :)
- Made scrollbar for terminal dark
- Added default terminal colors, to better fit the the rest of the theme.
- Added unity-greeter theme.
- Added line separators for menus and nautilus sidebar.
- Alot of other things I really can't remember.

## Screenshots

![Screenshot](http://i.imgur.com/xc8tiyR.png)
*arc-black-ubuntu. Have since changed a little bit, to #2f2f2f insted of #282828.*

![Screenshot](http://i.imgur.com/SfrUx19.png)
*Old Unity-greeter theme for lightdm, it's black-ish now, the rest is the same*

## How to install theme

```
sudo apt install git unity-tweak-tool gnome-themes-standard gtk2-engines-murrine
git clone https://github.com/vooze/arc-black-ubuntu
cd arc-black-ubuntu
sudo cp -R arc-black-ubuntu* /usr/share/themes
- Change theme in unity-tweak-tool
```

## How to update theme.

Since I quite frequenly (at least for now) is fixing some small bugs and adding more tweaks, you should probably check for updates, once in a while.
```
cd arc-black-ubuntu
git pull
## If there is no changes, there is no need paste/write the last 2 lines.
sudo rm -rf /usr/share/themes/arc-black-ubuntu*
sudo cp -R arc-black-ubuntu* /usr/share/themes
```

### How to change unity-greeter theme:

```
sudo cp -R arc-black-ubuntu/extra/unity-greeter/10_unity-greeter.gschema.override /usr/share/glib-2.0/schemas/
sudo glib-compile-schemas /usr/share/glib-2.0/schemas/
```

### Icon theme

This is very EARLY development, so please be gentle. It's right here: https://github.com/vooze/numix-blue-custom

### Credits:
- https://github.com/horst3180/ - For the arc-theme
- https://github.com/HEXcube - For the unity-greeter theme.
