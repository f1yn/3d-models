# RFridge Utensil Mounts

## Overview

Hang utensils on your fridge - great for condensed kitchens.

## Instructions

The default utensil holder can hold 4 utensils, and requires magnets. I used 
[these 12mm magnets for my mount](https://www.amazon.ca/gp/product/B07GX7Z4DF/), though feel free to use your own - they just
need to be round.

20% infill at .2mm or .3mm layer height is recommended. Extra vertical walls (i.e 4) will help make sure that heavy utensils
don't sag the hooks over time, and helps resist potential heat bursts if mounted near a stove or oven. This is especially
important for the peg extrusions.

I've also included a `.3mf` file to set up the print to behave the way I expect it to, feel free to modify.

### Parametric

The default `x4_zero.stl` file is meant for latering 2 rows of 4 utensils, though this can be adjusted. I've included
the FreeCAD file for this utensil holder, which can be adjusted to increase or decrease sizing/utensil count, magnetic
distribution of the mount.

Here's some of the more notable parameters you can change, though there are lots!

- `peg_distance` - the distance between mounted utensils (mm)
- `peg_diam` - the diameter of each peg (mm)
- `peg_count` - how many pegs to distribute (seperated by `peg_distance`)
- `peg_angle` - the angle of the peg (default is 45 deg - I'd recommend keeping it like that)
- `magnet_diam` - the width of magnets (mm)
- `magnet_count` - the number of magnets distributed on each side of the mount

# Lore

I don't like digging for my kitchen utensils. Having them easy to find and easy to see meant they are used more, and
encourage me to put them in the same spot after each meal and clean. 10/10 would utensil mount again.


# License
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg