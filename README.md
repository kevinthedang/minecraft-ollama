# Minecraft Ollama Integration [![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-darkgreen.svg)](https://creativecommons.org/licenses/by-nc/4.0/) [![Release Badge](https://img.shields.io/github/v/release/kevinthedang/minecraft-ollama?logo=github)](https://github.com/kevinthedang/minecraft-ollama/releases/latest)
It would be awesome to implement [Ollama](https://ollama.com/) into Minecraft as a Mod where you can talk to villagers and have a model that can watch your world and provide context to the player about what is happening in their world.

## Goals
* [ ] Implement Ollama into minecraft to interact with the player (kind of like an AI pal)
  * [ ] World Events context
  * [ ] Nearby villages context
  * [ ] Village context
    * For example, village was attacked my mobs, village built iron golem, village was raided
  * [ ] Villager context
    * For example, a villager can see a player, villager's friend died in the middle of the night
    * **NOTE**: Conversations likely limited to villagers with jobs 

## Mod vs Plugin?
* A ModPack will disassemble and assemble the game code to add something new into it when building the game.
* A Plugin respects the game code but adds on top of it, it can modify in this tree:
  * data
    * (namespace)
      * advancements (*.json)
      * functions (*.mcfunction)
      * item_modifiers (*.json)
      * loot_tables (*.json)
      * predicates (*.json)
      * recipes (*.json)
      * structures (*.nbt)

## Resources
* [Minecraft Forge](https://github.com/MinecraftForge/MinecraftForge)
* [Forge Modding Tutorials](https://moddingtutorials.org/)
* [Minecraft Wiki](https://minecraft.wiki/) for NPC interactions
  * [Structure](https://minecraft.wiki/w/Structure)
  * [Village](https://minecraft.wiki/w/Village)
    * [Villager](https://minecraft.wiki/w/Villager)
    * [Iron Golem](https://minecraft.wiki/w/Iron_Golem)
  * [Pillager Outpost](https://minecraft.wiki/w/Pillager_Outpost)
    * [Pillager](https://minecraft.wiki/w/Pillager)

## Acknowledgement
* [Kevin Dang](https://github.com/kevinthedang)

[minecraft-ollama](https://github.com/kevinthedang/minecraft-ollama) © 2023 by [Kevin Dang](https://github.com/kevinthedang) is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1)