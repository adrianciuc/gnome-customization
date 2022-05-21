# Change color for close, minimize and maximize buttons in Ubuntu 22.04

This repo contains customizations that can be applied to the default themes from Ubuntu 22.04 .

# Instructions

In Ubuntu themes are located in folder `/usr/share/themes`. For each accent color you can set from Settings, there is a coresponding theme. For example if you chose accent color blue, the Yaru-blue theme will be used. If you then change Ubuntu to dark mode, and keep accent color blue, the Yaru-blue-dark theme will be used. In order to edit the Yaru-blue-dark theme you must:

1. Open file `/usr/share/themes/Yaru-blue-dark/gtk-3.0/gtk.css`
2. Paste at the end of the file the code from this repository, from file custom.css
3. Open file `/usr/share/themes/Yaru-blue-dark/gtk-3.0/gtk-dark.css`
4. Paste at the end of the file the code from this repository, from file custom.css

In order to apply the changes, you cand go in Ubuntu in Settings > Appearance and choose differrent accent color and then, pick again the blue color so that Yaru-blue-dark theme will be loaded.


Note that this steps can be made for any Yaru theme that exists in folder `/usr/share/themes`.

## Warning

In case Ubuntu updates itself, and the Yaru-dark-theme is updated by Ubuntu updates, you will have to repeat the steps above 
