
# Rofi Configuration

This repository contains my custom Rofi configuration with image-based theming.

## Installation

1. Clone the configuration  
Copy the rofi directory into your Rofi config path:

cp -r rofi ~/.config/

2. Set up background images  
Create a directory for Rofi backgrounds and move your images there:

mkdir ~/.rofi-backgrounds

Place your background images inside ~/.rofi-backgrounds.

3. Reload Waybar (Arch Linux)  
If you’re using Waybar on Arch Linux, reload it so the changes apply.

## Usage

To launch Rofi with this theme:

rofi -show drun -theme ~/.config/rofi/image.rasi

## Keybinding (Sway)

If you’re using Sway, you can bind Rofi to a key combination.

Open your Sway config:

~/.config/sway/config.d/*

Add the following line (example uses Mod + D):

$mod+d exec $menu -show drun -theme ~/.config/rofi/image.rasi

## Notes

- Make sure rofi is installed and working before applying the config.
- Paths assume a standard Linux home directory layout.
- Tested on Arch Linux + Sway.
