# Pycolor
A colour sync tool

Pycolor is a small part of the larger project Pysync, coming soon. Pycolor sources colours from a user configured theme, and parses it into CSS, GTK, Rasi, and bash.

You can sync these files to other pieces of software, such as Waybar, GTK, Hyprland, Firefox, Discord, or Rofi, although it's alot easier with Pysync.

# Install

Just clone/download the two files, and move them to `.config/colours`.

`git clone https://github.com/asexylordrevan/pycolor ~/.config/colours`

You must be in said folder before running Pycolor, or it will not import colours correctly.

# Theming

The file `colors.py` located in `.config/colours` is your theme. It's written as a Python dictionary, so do not delete the top and bottom of the document. Change the colour names, or the colours, as desired. The default theme is Rosé Pine Moon. You cannot point at another configuration without Pysync, so if you use multiple themes, change your current theme's filename to `colors.py`.
