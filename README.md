# PAX ROMANA: Minority System
The Minority System mod is a project branched from the TC mod Pax Romana. We needed to represent the cultural and faith minorities of 263 BCE, but no mod created before really satisfied our needs. We wanted a system that added to the immersion of the game without changing its speed too much, making it neither too slow nor too fast.

So we've decided to create a new system, compatible with as many mods as possible and easily tweakable to everyone's liking.

## Features
Inspired by Total War: Attila, minorities here are represented by percentages, indicating the portion of the population in a region belonging to a certain culture or faith. Cultural and faith clashes can occur between different cultures or faiths not liking each other, or they can cooperate for the greater good. People now migrate in search of a better place when they lose wars, their county gets sieged, or their ruler is in huge debts. People lose faith if their ruler is a sinner but can start converting to his faith if the ruler is instead a pious individual.

## Compatibility
In general, this system makes for a more dynamic and immersive experience than the vanilla one, with compatibility with other mods in mind. In fact, this mod is compatible with most of the mods out there, except for:
- mods that edit the "window_county_view.gui" file
- mods that edit the court chaplain or the steward tasks
Any other mod should be 100% compatible!

## For modders
If you want to change the specific amount of culture and faith minorities of specific counties, do this:
- Copy this directory inside your main mod folder from the Pax Romana Minority System mod folder: "common/on_action/PAX_new_cultures"
- Now open the file "PAX_custom_minorities.txt" and edit it following the instructions written inside
- In the load order this mod should go before your mod, so that your mod can overwrite the file

# JOIN OUR DISCORD! -> https://discord.com/channels/735413460439007241/735413460766163110/1280506912986894458