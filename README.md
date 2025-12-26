
# Rofi Configuration

This repository contains my custom Rofi configuration with image-based theming.

## Installation

1. Clone the configuration  
Copy the rofitheme.rasi file into your Rofi config path:

cp -r rofitheme ~/.config/rofi

2. Set up background images  
Copy the .rofi directory you move your images there to ~/.rofi/.rofi-backgrounds:

Place your additional background images inside ~/.rofi-backgrounds.

3. Reload Waybar (Arch Linux)  
If you’re using Waybar on Arch Linux, reload it so the changes apply.

## Usage

To launch Rofi with this theme:

rofi -show drun -theme ~/.config/rofi/rofitheme.rasi

## Keybinding (Sway)

If you’re using Sway, you can bind Rofi to a key combination.

Open your Sway config:

~/.config/sway/config.d/*

Add the following line (example uses Mod + D):

$mod+d exec $menu -show drun -theme ~/.config/rofi/rofitheme.rasi

## Notes

- Make sure rofi is installed and working before applying the config.
- Paths assume a standard Linux home directory layout.
- Tested on Arch Linux + Sway.
- remember to check the similarity of names of the pics on the rofitheme.rasi config file and on the 
.rofi-backgrounds

