# GameXperience Project

## Goals
The goal is to create a PHP framework running dungeon crawlers. The framework will allow interaction of heroes and enemies in dungeons of variable size, loot, leveling and more. The idea is to keep it as customizable as possible so that anyone can pick it up to set up their own dungeon crawler, may it be a game, as part of a bigger project or a tool for game masters.

## Characters
Using the *Dungeons and Dragons* standards, characters will be defined by a certain number of stats:
* Strength (**STR**)
* Constitution (**CON**)
* Dexterity (**DEX**)
* Wisdom (**WIS**)
* Intelligence (**INT**)
* Charisma (**CHA**)
All those skills can be used to make tests throughout the game, but will especially impact the player's ability to fight. For instance, **STR** will impact the player's damage points and **CON** will impact the player's defense. For now, equations will be taken from *Dungeons and Dragons*, edition 3.5, but may be nerfed later.

Characters can also hold armor for head, chest, legs, feet and hands, as well as consumable items. Limitations to inventory size can be applied. Items are either to be worn or to be consumed. No quest items is planned for the moment (but it might later once the framework is in a working condition.

## Language
The framework is coded in PHP to ease testing, especially with interface (which I deem easier to create in HTML); however, a port to Java for use in Java and Android code is clearly envisaged once the framework's initial version works.

## Functionnalities
As for this version 1.0, the following functionnalities are to be programmed:
### Dungeon
* Randomly generated using a certain pool of pre-made rooms
* Can be modified with settings
* Turn-based actions
* Room or number of room passed objective 
* Possibility of stat tests and variable difficulty on actions

### Characters
* Character inventory
* Character armor
* Character main weapon
* Leveling XP Curve
* Character classes with spells accessible at certain levels
* Spells (with limited use)
* Team management up to 4 players
* Health 
* Main RPG stats

### Monsters
* Much like characters but with no inventory other than worn items
* Possibility of boss monsters
* Unique skillsets and inventories
* Loot from loot table after death

### Items 
* Only consumable or gear
