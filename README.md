# f23Final
Goofed the first one. Attempt 2 at creating a usable repo

This project will be a demo of combat for a basic roguelike RPG. 
One file of player save data will be kept and can be loaded or the data can be overwritten to start fresh. 

## What to expect

### Opening
After creating a new file, the player will be asked to choose one of the two offered weapons as their starting weapon.
They will then immediately go to a fight with a golem of a random element type. Player's element type is set to "Water" for now, 
but at later stages I want to create multiple heroes, each corresponding to one of the elements.

### Combat
Combat is relatively simple. The player selects a weapon to attack with and may choose to add elemental effects if desired. One must be careful, 
however, because each time a weapon is used, it loses durbility and will disappear from the inventory if durability reaches zero.

### Item management
Between combats, the player will pick up any weapons, armor, or items dropped by the enemy. Only four weapons may be in the inventory 
at a time. Before initiating the next round the player may choose to replace weapons or armor or use items,
which are also accessible during combat.

