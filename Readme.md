# Change color for close, minimize and maximize buttons in Ubuntu 22.04 for gtk 3 apps

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

# Change color for close, minimize and maximize buttons in Ubuntu 22.04 for gtk 4 apps

Note that the buttons will be bigger since I didn't found a way to make them the same size as the ones from gtk 3 apps

1. Open file `~/.zshrc`
2. Add this somewhere in it: `export XDG_CONFIG_HOME="$HOME/.config"`
3. create file `~/.config/gtk-4.0/gtk.css` and file `~/.config/gtk-4.0/gtk-dark.css`
4. Paste in those file the content from the file `custom-gtk4.css`


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

