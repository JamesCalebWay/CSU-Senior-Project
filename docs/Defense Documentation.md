Project Tarnished

November 24, 2023

James Caleb Way

Computer Science

Bachelor of Science

Dr. Sean Hayes

Statement of Purpose

Video games lack replay value and a way to solve this issue is with procedurally generated worlds, customization, and numerous secrets should be implemented into video games.

The ideal state of a video game is one that has a high replay value. If it has a high replay value, then the player will continue to come back to the game. Additionally, it allows the player to experience something new with each playthrough. However, many games are generic and do not offer diversity in gameplay which leads to games getting played only once. Video games need to have a high replay value so that people will continue to play them even after they finish them.

Replay value is very important. Many people will play a video game once and then never play it again. So, by providing the player with reasons to replay the game, they will be able to get more hours of enjoyment through multiple playthroughs. A few ways to encourage players to replay a game is with a vast number of achievements, secrets, alternate story lines, side quest, starting character classes, etc. All of these add to the replay value. Additionally, games like Minecraft and Valheim have replay value because they use procedural world generation. And unlike other games which have predefined worlds, worlds that are procedurally generated prevent the player from knowing where items, structures, bosses, etc. are so the player will need to search for them. Furthermore, games like Detroit: Become Human—who's story has over 40 different endings—encourages the player to replay the game multiple times to unlock all the endings. Likewise, Elden Ring and Dark Souls have multiple starting character classes for the player to choose from. This encourages the player to replay the game multiple times to experience the unique playstyle of each class.

To address the problem, I propose the implementation of a video game with procedural world generation and multiple weapon types for customization. This will allow players to have a new experience with each playthrough and allow them to see aspects of the game that they missed on their first playthrough. Also, it will create more diversity in how the player plays the game and would inspire them to play in a new way.

In conclusion, the lack of replay value of video games can be challenged with procedural world generation, multiple weapon types for customization, and numerous secrets for the player to find.

Research and Background

My research included learning how the wave function collapse algorithm works. I also studied how to use Unreal Engine 5. I had a limited understanding of Unreal Engine 4 which helped in my learning of Unreal Engine 5. After gaining some understanding of Unreal Engine 5 I had to learn how to implement wave function collapse inside the engine. My studying included but not limited to was the Unreal Engine 5 editor, YouTube, Gorka Games, Unreal Engine Forums, and the Unreal Engine Documentation.

Project Languages, Software, and Hardware

The project is implemented with Unreal Engine 5 using C++ and Unreal Engine Blueprints.

Requirements

| _ID#_ | _Type_ | _Description_ | _Rationale_ | _Fit Criterion_ | _Priority_ | _Dependencies_ |
| --- | --- | --- | --- | --- | --- | --- |
| _1_ | Functional | Open World video game | An open world video game will encourage replay ability | Is the game open world? | High | #16 |
| --- | --- | --- | --- | --- | --- | --- |
| _2_ | Functional | Different tiers of enemies including a boss tier | As the player gets stronger, they will be able to fight higher tier enemies and earn better rewards | Do enemies get stronger as the player progresses | High |
 |
| _3_ | Functional | Defeated enemies will drop loot | So that the player will be rewarded for defeating enemies | Do enemies drop loot and does the player get rewarded? | Medium | #2 |
| _4_ | Functional | Loot chest of various qualities | The player will be rewarded for finding chest in the environment | Does the chest contain loot and does the player get rewarded? | Medium |
 |
| _5_ | Functional | The player can customize their character (name and appearance) | Allows the player to have a more customizable experience | Can the player make a custom character? | Low |
 |
| _6_ | Functional | Player can earn experience points for defeating enemies | To allow the user to see their personal progression through the game | Does the player earn experience points for defeating enemies? | Medium |
 |
| _7_ | Functional | The player can spend experience points to level up their characters stats | The players character will be able to deal more damage to enemies and take more damage from enemies | Can the player upgrade their character's stats? | Medium | #6 |
| _8_ | Functional | Player can craft items from resource materials | The user will be able to craft health potions and arrows to restock their supply | Can the player craft items? | Medium | #3, 4, 9, 10 |
| _9_ | Functional | Player can forage plants | This will allow the user to get resources to craft items | Can the user forage materials from plants? | Medium |
 |
| _10_ | Functional | Player can buy items from the merchant | Player will be able to buy weapons, armor, health potions, and resources from merchants | Can the player buy items from the merchant? | Low |
 |
| _11_ | Functional | Player can equip armor | Equipping armor will allow the player to take less damage from enemy attacks | Can the player equip armor, and do they take less damage from enemy attacks? | Medium | #24 |
| _12_ | Functional | Player can equip weapons | Equipping weapons will allow the user to use a weapon that deals more damage or one that they prefer | Can the player equip different weapons? | Medium | #23 |
| _13_ | Functional | The player can user health potions | Using health potions will restore the character's health | Can the player use health positions, and do they regain health? | High |
 |
| _14_ | Functional | Merchants can sell items to the player | The merchant will have a limited supply of items, armor, weapons, resources, etc. that they player can purchase | Can the merchant sell items? | Low |
 |
| _15_ | Functional | Player checkpoints to set respawn points and restore health and health potions | The player will be able to rest at checkpoints, restoring health and health potions, but also respawning enemies | Can the player set a spawn point at a checkpoint and restore health and health potions? Do enemies respawn? | High |
 |
| _16_ | Functional | Procedural world generation | Allows the user to experience the game differently with each playthrough | Is each world/game different? | High |
 |
| _17_ | Functional | Enemy, chest, and plant spawn zones | Enemies, chest, and plants will spawn in certain regions based on their tier | Do enemies, chest, and plants spawn in the correct spawn zones? | High | #16 |
| _18_ | Functional | Game ends on death of final boss | When the player defeats the final boss, the game will end to inform the player that they beat the game | Does the game end upon final boss' death? | High |
 |
| _19_ | Functional | Player can kill merchants | Player can kill the merchants who will not respawn | Does the merchant respawn? | Low |
 |
| _20_ | Functional | Merchants will not restock their limited supply of items | This will cause the player to be carful of what they buy | Does the merchant have limited supply? | Low |
 |
| _21_ | Functional | Friendly NPC's will defend themselves if attacked | If the player or an enemy attack a friendly NPC (i.e., A merchant) they will defend themselves | Does the friendly NPC defend himself when the player attacks him? | Low |
 |
| _22_ | Functional | Character classes. Classes will have different stats and add difficulty to the game | Classes will provide replay ability by encouraging the player to try out all classes. Additionally, some classes will be more difficult to use than others | Are the classes different? Do they have different stats, and do they provide different levels of difficulty? | Medium |
 |
| _23_ | Functional | Different weapon qualities | Different tiers of quality for weapons will provide the weapon with different stats i.e., damage | Do the weapons have different damage amounts? | Low |
 |
| _24_ | Functional | Different armor qualities | Armor will have different tiers of quality meaning the better the quality the better the damage resistance | Does the armor provide different levels of damage resistance? | Low |
 |
| _25_ | Functional | Different weapon types, i.e., swords, spears, daggers, etc. | Each weapon type will have different attacks that deal different amounts of damage. Damage will also be affected by character class | Are the weapon types different in damage and attack? Is the damage affected by character class? | Medium | #22 |
| _26_ | Functional | Fast travel between checkpoints by using the map | The player will be able to travel between unlocked checkpoints | Can the player travel between checkpoints? | Low | #15, 27 |
| _27_ | Functional | Map that displays the player's current location, unlocked checkpoints, and merchant locations | This will allow the player to see where they are and plan where they want to go | Can the player open the map and view their current location, merchant locations, and unlocked checkpoints? | Medium |
 |
| _28_ | Functional | If the player dies, they will respawn at the last checkpoint they visited | If the player is killed by an enemy, then the player will respawn at the last visited checkpoint | Does the player respawn at their last visited checkpoint after they are killed? | High | #15 |

Implementation and Description

[Project Tarnished](https://github.com/JamesCalebWay/CSU-Senior-Project) is a melee combat video game where the player will traverse a procedurally generated world to fight enemies. When starting the game, the player will be presented with the main menu (fig. 1). From here the player can create a new game or load a previous save (fig. 2). If the player wants to create a new game, then they will need to choose a slot to save the game (fig. 3). If the player wants to load a previous game, then they can select the save slot to load the game (fig. 4). When the new game loads the player will spawn in the middle of the new map. But if the player reloaded a previous game, then they will spawn at a checkpoint (fig. 5) if they have interacted with one (fig. 6). To traverse the environment, the player can climb walls (fig. 7) and mantle ledges (fig. 8). When the player encounters enemies they can attack them with their fist, a sword, and/or bow (fig. 9). Whenever the player or an enemy takes damage, they will be staggered for a moment (fig. 10). Enemies will also try to attack the player (fig. 11). Defeated enemies will drop random loot (fig. 12) which the player can equip (fig. 13).

![](RackMultipart20231128-1-fs799e_html_26d1339c77f5cbb4.png)

(fig. 1: Main Menu)

![](RackMultipart20231128-1-fs799e_html_121859647693c121.png) (fig. 2: Play game menu)

![](RackMultipart20231128-1-fs799e_html_eb432fdb7fb4ccae.png) (fig. 3: New game menu)

![](RackMultipart20231128-1-fs799e_html_8ad954983edb2db.png) (fig. 4: Load game menu)

![](RackMultipart20231128-1-fs799e_html_cd5283f8decc5ba5.png) (fig. 5: Spawn at last saved checkpoint)

![](RackMultipart20231128-1-fs799e_html_1dca7008700c07fa.png) (fig. 6: Set respawn point)

![](RackMultipart20231128-1-fs799e_html_f2a8ef12f94f0ee9.png) (fig. 7: Climbing)

![](RackMultipart20231128-1-fs799e_html_2f55a80534623974.png) (fig. 8: Mantle ledge)

![](RackMultipart20231128-1-fs799e_html_816463b74d766fed.png) (fig. 9: Punching boss)

![](RackMultipart20231128-1-fs799e_html_58fa9b61b31dc57a.png) (fig. 10: Stagger boss)

![](RackMultipart20231128-1-fs799e_html_6b2bdc7f07527ebb.png) (fig. 11: Boss attacking player)

![](RackMultipart20231128-1-fs799e_html_9749c7b876f52c1e.png) (fig. 12: Enemies drop random loot)

![](RackMultipart20231128-1-fs799e_html_d2f81e06957dbd6e.png) (fig. 13: Equipment menu)

Test Plan and Results

| **Test** | **Instructions** | **Expected** | **Outcome** | **Notes** | **Passed** | **Failed** |
| --- | --- | --- | --- | --- | --- | --- |
| **Can game open?** | Click on desktop icon | Game will open and display home screen | **The game does launch** |   |
# pass
 |   |
| **Quit game from home menu?** | On the home menu click quit | The game will close when the quit button is pressed | **The player can exit to desktop from the main menu** |   |
# pass
 |   |
| **Load a save game?** | On home menu click load game | After clicking load game the terrain will be loaded from a previous save and the player will be at the last saved checkpoint | **The previous terrain loads, and player starts at the last checkpoint they interacted with** |   |
# pass
 |   |
| **Load a save game for each save slot?** | Same as Test#4 but for each save slot | Same as Test#4 but save slot should only load the game that was saved in its slot | **Each save slot loads its own save data** |   |
# pass
 |   |
| **Start a new game?** | On the main menu click new game | After clicking start, the terrain will be generated, and the player will be placed on it | **The player can start a new game from the main menu** |   |
# pass
 |   |
| **Create new game for each save slot?** | Same as Test#6 but for each save slot | Same as Test#6 but needs to be done for each save slot | **A new distinct game can be created for each save slot** |   |
# pass
 |   |
| **Delete/Overwrite a saved game?** | On the main menu, click new game and select the save slot to delete/overwrite. Confirm the overwrite. | After confirming the overwrite a new game will be created in that slot | **The old save will be overwritten with a new save** |   |
# pass
 |   |
| **Quit from within game?** | From within the game, press Esc key to bring up pause menu. Then click quit game | Game will close | **The player can open pause menu then click a button to quit to desktop** |   |
# pass
 |   |
| **Return to main menu starting from within game?** | From within the game, press Esc key to bring up pause menu. Then click exit to main menu button | Game will return to main menu | **The player can open pause menu then click a button to return to main menu** |   |
# pass
 |   |
| **Proper terrain generation?** | Start a game | Terrain will generate without any holes | **The terrain generates properly, i.e. no holes, or tile mismatch** |   |
# pass
 |   |
| **Can player damage enemies?** | Attack enemies | The player will deal damage to enemies when player attacks them | **The player can damage enemies** |   |
# pass
 |   |
| **Can enemies damage player?** | Enemies need to attack player | Enemies can damage player with them attack player | **Enemies can damage the player** | Enemies sometimes struggle to hit player |
# pass
 |   |
| **Do enemies drop loot?** | Attack and kill enemies | Killed enemies will randomly drop items. Sometimes they won't drop any items | **The enemies drop random items, weapons, arrows, armor, shield** |   |
# pass
 |   |
| **Can player pick up items?** | Pick up item using corresponding button | Player can pick up items by pressing button | **The player can pick up dropped items** |   |
# pass
 |   |
| **Can player equip items?** | Open inventory menu and select item to equip | Player can equip items to improve stats | **The player can equip the items that are in their inventory** |   |
# pass
 |   |
| **Can enemies see and follow player?** | Walk in front of an enemy | When the player is inside the enemy's sight of view then enemy will move toward player and attack | **Enemies can see and follow the player** | Enemy AI loses sight of player easily |
# pass
 |   |
| **Player respawns?** | Die | When player dies, they will respawn at the last visited checkpoint | **The player respawns at the last visited check upon death. If the player did not visit a checkpoint, then they respawn at the initial spawn point** |   |
# pass
 |   |
| **Can player block damage?** | Hold corresponding key to block | Player will block incoming damage when using block (hands, sword, etc.) | **The player cannot block** | There is not a blocking mechanic |   |
# fail
 |
| **Does blocking slow movement?** | Hold corresponding key to block | If player is blocking, then their movement speed will be decreased | **Blocking is not implemented** | The shield can be equipped to back but serves no function |   |
# fail
 |
| **Do the proper animations play for each task?** | Perform tasks that have animations | Running, jumping, walking, fighting, etc. will have correlation animations | **The assigned animations play for the assigned events** |   |
# pass
 |   |
| **Do the proper sound effects play for each task?** | Perform tasks that have sound effects | Punching, walking, crafting, dying, etc. will have a correlation sound effect | **The assigned sound effect plays for the assigned events** | Due to lack of funding some sound effects are more of placeholders |
# pass
 |   |
| **Does the health bar update?** | Take damage, visit checkpoints | The health bar will decrease when the player takes damage and will restore when player visits a checkpoint | **The health bar does update when the player takes damage and when visiting checkpoints** |   |
# pass
 |   |
| **Are health potions restored when player visits checkpoint?** | Use health potion(s) then visit checkpoint | Health potions will be restored when the player visits a checkpoint |   |  Health potions are not implemented |   |
# fail
 |
| **Do weapons deal different amounts of damage?** | Check the amount of damage each weapon deals | Each weapon will deal a different amount of damage within a range | **Each weapon has a different base damage amount** |   |
# pass
 |   |
| **Do shields block incoming damage?** | Block attack with the shield | Sheilds will block up to a certain amount of incoming damage | **Sheilds do not block damage** | The shield can be equipped to hand but serves no function |   |
# fail
 |
| **Can Player vault short walls?** | Walk over to wall and press assigned vaulting button | The player will climb and jump over wall or obstacle | **The player can vault over short walls** |   |
# pass
 |   |
| **Does player movement slow when player is crouched?** | Press assigned crouching button | When the player is crouched the player's movement will be decreased | **When crouched the player's movement speed is slowed** |   |
# pass
 |   |
| **Do enemies wander when not seeing the player?** | Check if enemies wander when they do not see player | Enemies will be walking around | **Enemies do wander when not seeing the player** |   |
# pass
 |   |
| **Can player jump?** | Press assigned jump button | Player will jump | **The player can jump** |   |
# pass
 |   |
| **Can player walk?** | Use assigned movement keys | Player will walk in the direction corresponding to assigned movement keys | **The player can walk** |   |
# pass
 |   |
| **Can player run?** | Use assigned running and movement keys | Player will run in the direction corresponding to assigned movement keys | **The player can run** |   |
# pass
 |   |
| **Player must not vault over enemies** | When near enemy press assigned vault key | Player must not vault over enemy. (Note: Player is allowed to jump over enemies if able) | **Player cannot vault over enemy AI** |   |
# pass
 |   |
| **Do Enemy spawners spawn selected Enemies?** | Check if spawners spawn the correct enemy kinds | Spawner will spawn selected enemies | **Spawners only spawn the selected enemy types** |   |
# pass
 |   |
| **Do enemies spawned from spawners and exhibit enemy traits?** | Spawn enemies from spawner and check for enemy characteristics | Attack when they see player, wander when they don't see player, etc. | **Enemies can spawn and they move, attack player, and stop when they can't see player** | Enemy AI could use improvements in player detection |
# pass
 |   |
| **Is player UI visible?** | Start a game | Player UI will display player health, stamina, level. | **The player UI is visible in gameplay** |   |
# pass
 |   |
| **Does player's stamina decrease when running?** | Run | Stamina bar will decrease when player runs | **The player's stamina decreased while running** |   |
# pass
 |   |
| **Does player movement slow when stamina is depleted?** | Move when out of stamina | Movement will be decreased when player is out of stamina | **When stamina was depleted the player's movement speed slowed** |   |
# pass
 |   |
| **Does player character ragdoll when defeated?** | Die | The player character will ragdoll when defeated | **Player does not ragdoll when killed** | Ragdoll was disable because it caused issues with respawning |   |
# fail
 |
| **Do enemies ragdoll when defeated** | Kill enemies | Enemies will ragdoll when they die | **Enemies ragdoll when they are killed** |   |
# pass
 |   |
| **Can player dodge?** | Press assigned dodge key | Player will dodge | **The player can dodge roll** |   |
# pass
 |   |
| **Can player climb wall?** | Next to wall press the assigned climb key | Players will grab onto the wall. The player can climb up, down, left, and right | **Play can climb the wall** | Sometimes the player turns around while climbing a wall. This prevents the player from climbing |
# pass
 |   |
| **Can player mantle ledge while climbing?** | Climb wall up to a ledge | When near the ledge the player will mantle the ledge and switch back to walking state | **The player can mantle ledges** |   |
# pass
 |   |
| **Does arrow count increase when player picks up dropped arrows?** | After enemy drops arrows pick them up | The player's arrow count will increase after pickup | **The arrow count increases after pickup** |   |
# pass
 |   |
| **Can the player switch between the bow and sword? Player can switch to fist?** | Press assigned weapon keys | When the weapon button is pressed the weapon will be equipped to hand. If the assigned button is pressed twice then no weapon will be equipped to hands; player can now use fist. |   |   |
# pass
 |   |

Challenges Overcome

The biggest challenge overcame was the implementation of the Wave Function Collapse algorithm and getting it to run when playing the game (packaged or in editor). Also, learning how to make a video game took a lot of time, trial, and error. Another challenge was I had to figure out what features needed to be pushed to the backburner or cutout entirely. Because I learned that a simple little feature of a video game is not nearly as simple as I thought. Each feature has a bunch of other features and each of those features need to communicate with each other and with other different components.

Presentation Slides

![](RackMultipart20231128-1-fs799e_html_776b3193d95978be.png)

![](RackMultipart20231128-1-fs799e_html_6a0bb388b207fece.png)

![](RackMultipart20231128-1-fs799e_html_e1ec70c04fabb8da.png)

![](RackMultipart20231128-1-fs799e_html_ce001aa52ac8d048.png)

![](RackMultipart20231128-1-fs799e_html_b516f7266916af8.png)

![](RackMultipart20231128-1-fs799e_html_ef3354e19d5faa67.png)

![](RackMultipart20231128-1-fs799e_html_de0c1406f817f186.png)

![](RackMultipart20231128-1-fs799e_html_61a4c508f57abebc.png)

Future Enhancements

There are too many features that could be added to list out here so I would cover some of the more main ones.

The WFC algorithm could use a function that could rotate tiles to check if they could be used with the current adjacencies. This tile rotation function would shorten the tile list because instead of using 4 tiles to represent each rotation it could use just 1 tile. This would greatly speed up the creation of new tile types. Also, more tile types would add more diverse terrain and different biome types.

The AI also needs optimization. AI enemies really hurt the game's frame rate, especially if there are a bunch of enemies. Also, the enemy AI needs improvements in behavior and player detection. Right now, enemy AI is very basic; they only have a wander state, attack state, and investigate state. More states would be very beneficial to the AI. Additionally, it would be good to create more enemy types like ones with different weapons, difficulties, armor, shields, self-healing, etc. The same goes for boss enemies.