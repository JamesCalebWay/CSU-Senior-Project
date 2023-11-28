Test Plan for Project Tarnished

This document is designed to test the various aspects of the game. These aspects include the product's functionality and specification. The test listed will be done within the Unreal Engine 5 Editor as well as the packaged product.

For more information on the functionality and specification view the [Requirements](https://github.com/JamesCalebWay/CSU-Senior-Project/blob/master/docs/Requirements.md) and [Proposal](https://github.com/JamesCalebWay/CSU-Senior-Project/blob/master/docs/Proposal.md) documentation.

Testing will take place within the Ureal Engine 5 Editor and within the packaged product on a system running Windows 10.

Testing will continue if the remaining tests are independent of the previous tests. If a test fails, then the system being tested will be reworked and/or re-evaluated. All failed systems that have been updated will be tested again.

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
| **Can player block damage?** | Hold corresponding key to block | Player will block incoming damage when using block (hands, sword, etc.) | **The player cannot block** | The is not blocking mechanic |   |
# fail
 |
| **Does blocking slow movement?** | Hold corresponding key to block | If player is blocking, then their movement speed will be decreased | **Blocking is not implemented** | The shield can be equipped to hand but serves no function |   |
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
| **Are health potions restored when player visits checkpoint?** | Use health potion(s) then visit checkpoint | Health potions will be restored when the player visits a checkpoint |   |   |   |   |
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
| **Can the player switch between the bow and sword? Player can switch to fist?** | Press assigned weapon keys | When the weapon button is pressed the weapon will be equipped to hand. If the assigned button is pressed twice then no weapon will be equipped to hands; player can now use fist. |   |   |   |   |