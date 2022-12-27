
# Player Actions and Motivations

## Introduction

**The tools available to player and the desires when choosing tools.**

----------

## Content

|1|The observable world is split up into evenly sized tiles. Entities such as the player, enemies and items take up a tile space.|
|--|--|
|2|The player using their feet may move a single tile provided the tile does not contain a blocking instance. Blocking instances include walls, characters (enemies included) and doors for which they do not have a key.|
|3|Every time the player moves these counts as an action. Attacking counts as an action. Item use counts as an action. Opening a door, interacting with an interactable and special movement such a jumping count as actions.|
|4|Every other entity in the area may then take their action. Their actions may include anything the player can do and are dictated by artificial intelligence.|
|5|Players have attributes such as health. If health reaches zero (or below) the player is dead. Enemies, traps (dangerous tiles) and the environment is attempting to reduce the player’s health.|
|6|Players and enemies attempt to reduce one another’s health through attacks. Attacks have a range in tiles and statics used to determine the damage. Enemies wish to defeat the player. Enemies drop valuable on death which may aid the player.|
|7|Player attacks occur by selection of a weapon and then activation (firing). Players are aware if the attacks land on enemies and if the attack was effective. They are aware visually on the Enemy and in turn they are aware of their own damage in the same way.|
|8|Players acquire weapons and items via enemy drops. Players may find weapons and items in the world, within containers or in hard-to-reach places requiring items for movement. Some areas are closed off and require interactions to unlock, those areas may contain items.|
|9|  |
|10|  |
|11|  |
|12|  |
|13|  |
|14|  |
|15|  |
|16|  |
|17|  |
|18|  |
|19|  |
|20|  |
|21|  |
|22|  |
|23|  |
|24|  |
|25|  |
|26|  |
|27|  |
|28|  |
----------

## Why

The action system presented gives an unlimited time for thought and reasoning between moves. This is the Rouge system of actions. It is such that creates tension between the Player and game to select the correct move.

Features of such a system require a setup which clearly define the rules and world. These features are defined in the design as:

* Tiles – the player clearly understands the movement system. They understand how close or far any unit may be.
* Attacks, Item Use and Movement are actions – The player clearly understands that diegetic actions affect the world and hence time in the world. As menu use would not affect this, non-diegetic actions are non-time based.
* Health – is a very well-established attribute in games. This is shorthand familiarity with the concepts of life.
* Other Entities – People tend to understand the concepts of others by the time of teenage hood. Provided the enemies roughly have the abilities of the player this continuity should ensure that the rules are clearly defined i.e., you are not the only thing in this world able to act.

These turn based systems tend to work on single player levels as they are not large-scale battles (Civilizations) but instead single hero battles moving through the world. The reasoning behind a single hero battle is to unite the human playing the game with the player. A story may be built with the avatar and player if they are actively controlling the player. Customisation is also much more apparent when such may also affect the flow (or actions) in the game.


## Design Risks

Decision pacing may become an issue if there are too many variables for the player to decide upon. This element means that the player spends more time making the decision than performing actions within the game. Making the actions less consequential means that more thinking is advantageous because no decision is ever incorrect, and less penalisation has the same effect. This should be kept in check by reducing the elements which may affect a given decision at any one time and therefore make the calculation for the player clearer and the risks clearer. 

*Designing games – Tynan Sylvester 2013*

Multiplayer may become more difficult with this in mind, locking it out entirely. This is not a deal breaker but something to be kept in mind. It would be possible still however should be defined in a separate document that would be possible. The mitigation is to not have multiplayer for the most part as most of this game is likely to be scaled for single player then to explore a multiplayer game mode with levels scaled for multiplayer. 

## Background Research

![Methods to show information for a player. A floor marker (highlight floor). Point to them with an arrow. Make them glow (damage or power). Cover them in goo/position for damage and show heath bar to show damage taken.](https://github.com/PhonographMan/Tamago-PublicGameProject/blob/main/GameDesign/Resources/ScottRodgers-LevelUp-272-A.png?raw=true)

*Level Up – Scott Rodgers (pg. 272)*

On interface Rogers identifies the three key methods to identifying key information on a player. Understanding spatial awareness is key to the player knowing their actions and their involvement in the world. Understanding who they are is important, in this instance they use markers which isn’t always required but may be. Indication of damage is important, or indication of increased / taken damage is vital to ensure the player understands their actions. Health bars are also another great technique for this writes Rodgers as they double up as an arrow and non-diegetic user interface.

----------

## Considerations

> **What other departments or sections of the game should be considered or might require additional technology to create this feature.**

### Game Rating

> **Does this feature have the ability to raise the rating?**

### Patents, Trademarks and Copyright

> **Does this overlap with existing patents, could this be patented.**

### Build and Systems

> **Is there any big data processing required to get this feature working.**

### Tools

> **Do we require more tools to make this work and allow designers to use this feature.**

### Save file implications

> **Will this affect how the game saves / loads data and what might that be.**

### Performance Implications

> **Will this affect performance in some way? Would we need to increase the target machines to play the game?**

### Effect on other systems

> **Might this affect other systems such as economical, battle or exploration.**
