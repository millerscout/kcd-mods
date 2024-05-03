# Read Me

## Description

This mod makes some commonly stacked items weightless. Those are : 

* **Bandages**
* **Lockpicks**
* **Repair Kits**
* **Alchemy Items (Herbs & Special)**
* **Potions, Poisons and Spirits**
* **Arrows**

The goal is to remove the tedium of inventory management for these items by discarding the need to constantly transfer them to and from the global chest.

Note however that I *had* to modify the price of all these items ; otherwise, the game would consider that these lines weren’t modified for some reason so XML patching wouldn’t work. 

So for the most part, I changed them to a close “*quarter*” number. (25, 50, 75, 100 and so on.) That’s not a big difference actually since 10 equals to one Groschen, not 10.

Exceptions :

* **Repair Kits**. Made them roughly twice as expensive. They are way too accessible early game and most people will steal them later on anyway (or have well enough money to buy them). 
* **Arrows**. +10 (1 Groschen) to each price just so the changes take effect. Researching what corresponds to each arrow sounded like a pain. 

## Installation & Tweaking

Unzip and drop into your mod folder. Add it anywhere to your `mod_order.txt` if you have one.

Since it uses XML patching, it’s easy to edit everything to your liking. Open the `.pak` with 7-Zip* and use a text editor to configure the `Weight="0"`, save and accept 7-Zip’s prompt. You can also edit the prices, but make sure not to revert them to their default value.

*You can also use other archive managers, but 7-Zip usually doesn’t fail to save files once you’re done.

## XML Patching

And a little *how to* as a bonus because why not, it’s useful.

1.9.3. introduced a way to patch XML files instead of overwriting them completely. To achieve that, 3 steps are necessary :

1. Specify the Mod’s name in `mod.manifest`.
2. Name the `.pak` archive according to the previous point.
3. Add `__Your_Mod’s_Name` after each XML file in the archive.

The Mod Folder’s name doesn’t matter though. 

Doesn’t work with some files for some reason. Probably because of the name. For instance, if you want to patch something in English in Localization, you’ll have to name your file `text__Your_Mod’s_Name.xml` no matter what file it is supposed to patch.

## Planned

Nothing. Don’t think I missed anything but hit me up if I did. 

Or if you think something should be added. Just keep in mind that the goal isn’t to make everything weightless, just to remove the need to use carry weight tweaks by eliminating the tedium of transferring stackables to and from the global chest.

## Changelog

1.3

* Updated to work with newer game versions according to the comments on the mod’s page.

* Added `<description>This mod makes some commonly stacked items weightless.</description>` in mod.manifest.

* Renamed the folder to `Weightless_Stackables`.

1.2

- Renamed mod to “*Weightless Stackables”.
- Incidentally made all concerned items weightless. Why deal in half measures ?
- Added some comments to the XML to make it easier to tweak yourself.

1.1

* Added Bandages, Lockpicks and Special Alchemy Items.

1.0

* Initial release with Herbs, Arrows and Repair Kits.