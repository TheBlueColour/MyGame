# FGCT4015: Fundamentals of Games Development 25/26

### Zuzanna Pawelczyk

### 2506784

### Repository Link
### Build Link
### Demo Video


## Abstract 

My goal is to create a Unreal Engine 3D game, focusing on the style of platformer with inspiration being Sonic games. My plan is to create a platformer where the task is to collect a certain amount of coins before reaching the end goal and finishing the game. You play as a little creature avoiding spike enemies that try to damage you and traverse moving platforms, disapearing platforms, wall jumping and springs. 

My Goals:
    A Moving Actor in the form of moving platforms around the map that the player has to traverse over, the platforms can range from ones that move on the x-axis or on the y-axis. As well as disapearing platforms once you stand on them that reapear after a certain amount of time. 
    An AI behaviour tree to create an enemy for the player to avoid, the enemy would patrol around their section of the stage and have a limited view infront of them that when the player walks infront the enemy locks on the player and follows them, damaging them if they colide with the enemy. The enemy would not be able to be killed.
    An interface where when the player clicks a certain button it interacts with the object in a certain radius around the player. This could be used for the ending goal, if the player reachs the end the can click the E button to interact with the goal, if they have enough coins to succeed the game will progress to a win screen and then stop the game, if they do not have enough coins then the game continues until they succeed.
    An Event dispatcher, where one actor changes, other objects are aware of the change and respond to this change. This can be used for the coins to spawn them all back in once the player dies. 
    A collection or array to store values like a score.
    A variable that is editable directly in the editor so that it's easier to change outside of the blueprints, for example the health of the player character.
    A UI to show the health, coin collections and instructions to what the player must do to beat the game. I would need an UI for the begining of the game for the player to start the game or quit or look at the controls, as well as display to the player when they have won the game. As well as add sound for the coin collection as well as background ambience music for the game.

## Research

### Methodology

I will approach my work by looking through Sonic games that focus on the 3D platformer style, to see what elements the game has that i could try and implmenet into my own game. I will be looking at examples through youtube tutorials on how to use Unreal and it's blueprints. 

### Games Sources


