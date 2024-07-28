# Loottable Autosmelt
A Minecraft Datapack that uses loot tables to add the ability for tools to auto smelt mined blocks. Also includes the ability to void common block drops like cobblestone.

This datapack includes support for Weld by default, however if you wish to edit the loot tables beyond this library you will need to edit the Weld rules.

## Enchantments
As of version 2.0, Loottable Autosmelt adds 2 custom enchantments: `loottable_autosmelt:autosmelt` and `loottable_autosmelt:trash`. Simply add these to any item you wish to have these features. NBT data is no longer supported.

By default, these enchantments are not accessible via survival in any way.

## How to use
1. Copy the contents the `data/minecraft` folder into your data pack.
2. Add the contents of `assets` to your resourcepack folder (localizations for the enchantment names)
3. Manually merge any conflicting loot tables you may have. Be sure to modify the Weld rules.
4. Implement the API as described above.

For easier mangament of dependencies, check out my project [Datapack Build Manager](https://github.com/ICY105/DatapackBuildManager).
