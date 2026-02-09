# Overgeared – Mod Compatibility Datapack

This datapack adds **recipe compatibility** for **[Overgeared](https://www.curseforge.com/minecraft/mc-mods/overgeared)**, integrating items and materials from other mods into Overgeared’s progression and crafting systems in a consistent, intuitive way.

The idea is to make Overgeared **play nicely with a broader mod ecosystem**, without breaking immersion or player expectations.

***

## Features

*   Adds Overgeared-compatible recipes for items from supported mods
*   Focuses on logical integrations rather than aggressive rebalancing
*   Lightweight datapack — no scripts, no performance impact
*   Safe to add to existing worlds

***

## Supported Mods

This datapack currently adds compatibility for:

*   **Apotheosis**
*   **Aquaculture 2**
*   **Aquaculture Delight**
*   **Archbows**
*   **Dungeon’s Delight**
*   **\[Let’s Do\] Farm & Charm**
*   **\[Let’s Do\] Herbal Brews**
*   **Farmer’s Delight**
*   **Hardcore Torches**
*   **Iron’s Spells and Spellbooks**
*   **Jaden’s Nether Expansion Delight**
*   **Locks – Unofficial**
*   **Minecraft Comes Alive**
*   **Macaw’s Roofs**
*   **Macaw’s Windows**
*   **Some Minecraft recipes that use iron**
*   **Jaden’s Nether Expansions**
*   **Nether’s Delight**
*   **No Tree Punching**
*   **Runic Enchanting**
*   **Realm RPG: Sea Dwellers**
*   **Smallships**
*   **Thin Air**
*   **Tough As Nails**
*   **TheDragon’s Traps Mod**

***

## Requirements

*   **Minecraft Java Edition 1.20.1**
*   **Overgeared** mod

***

## Installation

### Singleplayer

1.  Download the .zip file from this website
2.  Open your Minecraft saves folder
3.  Place the datapack folder into:  
    `saves/<your_world_name>/datapacks/`
4.  Place the datapack also into the resourcepack folder and select it for loading (this will update the language files for tool types) `minecraft/resourcepacks/`
5.  Launch the world
6.  Run `/reload` or re-enter the world
7.  Confirm installation with `/datapack list`

### Multiplayer / Server

1.  Stop the server
2.  Place the datapack folder into:  
    `<server_root>/world/datapacks/`
3.  Place the datapack also into the resourcepack folder and select it for loading (this will update the language files for tool types) `<server_root>/resourcepacks/`
4.  Start the server
5.  Run `/reload` if the world is already loaded

***

## Configuration

For certain mod compatibilities, I've included new tool types for blueprints, however Overgeared requires the configuration file to be updated with this new list, which this datapack cannot overwrite.

To configure this, go to your instance folder and navigate to config and look for overgeared-common.toml. In there, look for a line that contains `availableToolTypes` and replace the entire value after the `=` sign with this:

`["sword", "axe", "pickaxe", "shovel", "hoe", "knife", "fillet_knife", "machete", "cleaver", "mattock", "bow", "helmet", "chestplate", "leggings", "boots", "horse_armor"]`

***

## Issues & Contributions

If you encounter:

*   Missing integrations
*   Recipe conflicts
*   Balance concerns
*   Suggestions for additional mod support

Feel free to open an **issue** or submit a **pull request**.

Contributions are welcome!

***

## License

This project is licensed under the **MIT License**.

You are free to:

*   Use it in modpacks
*   Modify it
*   Redistribute it
*   Fork it for your own projects

As long as you include the original license and copyright notice.  
See the `LICENSE` file for full details.

***

## Credits

*   **stirdrem** — Author of Overgeared mod
*   All supported mod authors for their excellent work

***

Forge onward ⚙️
