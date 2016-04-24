# Arc Darker Ubuntu

Not really a coder, but this is my attempt at making the arc-theme at bit more unity-friendly.

This theme is build with GTK3.18 in mind, so it's for Ubuntu unity 16.04 ONLY. - If you dont like OSX icons,  you  can use the orignals with theme noOSX.

Theme is a fork of https://github.com/horst3180/arc-theme/ - Thanks to horst3180 for his wonderful theme.

If you have more suggestions feel free to ask or make pull-requests.

You will need to install gnome-themes-standard & gtk2-engines-murrine to make sure everything works.

# Changes made

- Disabled transparency
- Made the unity top bar the same color as other windows.
- Added OSX icons (there is a version without them as well)
- Deleted all non-unity stuff
- Made menus blue/white instead of white/black, which made some problems for the unity top bar - icons would not show in the correct color. - White icons on white background is ugly :)
- Fixed GTK calendar a bit
- Fixed sound-buttons in unity-panel
- Made scrollbar for terminal dark
- Added unity-greeter theme.
- Other unity-stuff.

# Screenshots

![Screenshot](http://i.imgur.com/BJbLRGF.png)
*Blue menus instead of white, OSX icons and dark scrollbar for Gnome Terminal.*

![Screenshot](http://i.imgur.com/SfrUx19.png)
*Unity-greeter theme for lightdm*

# How to install theme

```
sudo apt install git unity-tweak-tool gnome-themes-standard gtk2-engines-murrine
git clone https://github.com/vooze/arc-darker-ubuntu
cd arc-darker-ubuntu
sudo cp -R arc-darker-ubuntu /usr/share/themes
- Change theme in unity-tweak-tool
```

# How to change unity-greeter theme:

```
sudo cp -R /THEME-FOLDER-CHANGE-THIS/extra/unity-greeter/10_unity-greeter.gschema.override /usr/share/glib-2.0/schemas/
sudo glib-compile-schemas /usr/share/glib-2.0/schemas/
```

# Credits:
- https://github.com/horst3180/ - For the arc-theme
- https://github.com/HEXcube - For the unity-greeter theme.
