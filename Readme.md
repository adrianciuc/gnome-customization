# Change color for close, minimize and maximize buttons in Ubuntu 22.04

This repo contains customizations that can be applied to the default themes from Ubuntu 22.04 .

# Instructions

1. Open file (create if does not exists) `~/.config/gtk-3.0/gtk.css`
2. Paste the css code, from file `custom.css` from this repository
3. Logout and Login

If you have Firefox installed as Snap:

1. Open file (create if does not exists)`~/snap/firefox/current/.config/gtk-3.0`
2. Paste the css code, from file `custom.css` from this repository
3. Logout and Login

Note that this steps can be made for any Yaru theme that exists in folder `/usr/share/themes`.

# Change Gnome Terminal colors

1. Install `dconf`
2. Download the file `gnome-terminal-profiles.dconf`
3. Open a terminal in the folder where you downloaded the file and run `dconf load /org/gnome/terminal/legacy/profiles:/ < gnome-terminal-profiles.dconf`
4. Close all terminals (maybe logout and login)
5. Open a terminal window and go to Menu Button > Preferences > Profiles
6. Chose profile named `custom-stuff (Copy)`
7. Click on the arrow and click Set as default


# Screenshots 

## Close, maximize, minimize buttons

![image](https://raw.github.com/adrianciuc/gnome-customization/main/buttons.png)

## Terminal colors

![image](https://raw.github.com/adrianciuc/gnome-customization/main/terminal.png)


# Issues

On Snaps applications the close, maximize and minimize buttons are not sized accordingly so they have the default size and space between them. Also the close, maximize and minimize icons are showing permanently, not only when hovering with mouse cursor. Here is how snaps look like (Firefox in front and Visual Studio Code in the back)

![image](https://raw.github.com/adrianciuc/gnome-customization/main/snaps.png)

