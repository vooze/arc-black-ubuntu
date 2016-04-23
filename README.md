# Arc Darker Ubuntu

Not really a coder, but this is my attempt at making the arc-theme at bit more unity-friendly.

This theme is build with GTK3.18 in mind, so it's for Ubuntu unity 16.04 ONLY. - If you dont like OSX icons,  you  can use the orignals with the "non-OSX" branch.

Theme is a fork of https://github.com/horst3180/arc-theme/ - Thanks to horst3180 for his wonderful theme.

If you have more suggestions feel free to ask or make pull-requests.

# Changes made

- Disabled transparency
- Made the unity top bar the same color as other windows.
- Added OSX icons (there is a version without them as well)
- Deleted all non-unity stuff
- Made menus blue/white instead of white/black, which made some problems for the unity top bar - icons would not show in the correct color. - White icons on white background is ugly :)
- Fixed GTK calendar a bit
- Fixed sound-buttons in unity-panel
- Made scrollbar for terminal dark
- Other unity-stuff.

# Screenshot

![Screenshot](http://i.imgur.com/Bhz3o8z.jpg)
*Blue menus instead of white, OSX icons and dark scrollbar for Gnome Terminal.*

# How to install

```
(sudo apt install git)
git clone https://github.com/vooze/arc-darker-ubuntu
sudo cp -R arc-darker-ubuntu /usr/share/themes
- Change theme in unity-tweak-tool
```
