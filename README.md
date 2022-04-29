# Loot-table Autosmelt
A Minecraft Datapack that uses loot tables to add the ability for tools to auto smelt mined blocks. Also includes the ability to void common block drops like cobblestone.

## NBT Format
These are NBT data specifications for items, storage, or entities that hold special data.

```
Add this tag to any item that should smelt mined blocks:
Item.tag{auto_smelt:1b}
```

```
Add this tag to any item that should destroy common block drops:
Item.tag{void_drop:1b}
```

## How to use
1. Copy the contents the `data/minecraft` folder into your data pack.
2. Manually merge any conflicting loot tables you may have
3. Implement the API as described above.

For easier mangament of dependencies, check out my project [Datapack Build Manager](https://github.com/ICY105/DatapackBuildManager).
