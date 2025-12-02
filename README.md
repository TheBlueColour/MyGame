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

I will approach my work by looking through Sonic games that focus on the 3D platformer style, to see what elements the game has that i could try and implmenet into my own game. I will be looking at examples through youtube tutorials on how to use Unreal and it's blueprints. Near the end of my game progresss I had 8 people do a guided test to observe how people react to my game and what issues they have.

### Games Sources

My initial point of inspiriation is Sonic Generations. 

![alt text](image.png)

This game is created by Sega in 2011 for their 20th aniversary, it's an extremely popular game that got a remake in 2024 adding more content. The game has both 3D and 2D gameplay with overall 3D models, the game is linear with minimal branch paths to get to an end goal. On the way to the goal, Sonic runs through collecting rings, bouncing off springs and avoiding different robotic enemies. Sonic also has the ability to double jump, stomp and wall jump on certain specific walls which I want to add into my own game. In a stage called Green Hill, there are platforms that fall once Sonic steps on them, after a certain amount of time they reapear for Sonic to be able to walk over them again, this inspired me to create my own disapearing platforms. 

My second inspiration was Sonic Adventure 2.

![alt text](image-1.png)

Sonic Adventure 2 is a game created in 2001 for their 5th aniversary as a last resort to save the franchise, which allowed the franchise to continue on due to it's success. Contrary to Sonic Generations where the stages are more linear and it does not have the boost formula therefore there's more time to explore the stage overall than having to run straight through the stage. As I cant replicate the boost formula and the length and extreme speed of the Sonic Generations stage, I am taking Sonic Adventure 2 as inspiration for the layout of stages and for the slower approach for the stage. In the stage, City Escape, there are platforms that are tubes that move up and down to cross bottomless pits, this was my inspiration for the moving platforms. 

### Doccumentation Sources 

To help with making the game I used a multtitude of different youtube tutorials as sources as well as the official Unreal Websites as help to figure out different elements of my game that I wanted to include.

(Learn Blueprints in Unreal Engine 5 - Beginner Tutorial) I used this video to help with learning how to initially learn blueprints within Unreal as this is my first time using Unreal. This was insanely helpful to learn the basics of Unreal. 

(How to Make a Moving Platform in Unreal Engine 5)

(How To Make Disappearing/Reappearing Platforms In Unreal Engine 4 - UE4 Tutorial) I used this to learn how to make platforms disapear with their visibility and reapear after a certain time or once being collided with, this is very useful as actors that are destroyed can not be restored easily in Unreal so instead of destroying them I can make them disapear. 

(How to Make A Behavior Tree in Unreal Engine 5 Tutorial ( Complete Guide )) With this I was able to create an enemy AI and allow the AI behaviour to walk and patrol around the area, moving to a random area after waiting for a few seconds to keep look out for the player.

(Event Dispatchers | Unreal Engine 5 Tutorial) I used this to help with the coins that needed an event dispatcher to spawn back in after the player dies. 

(The Easiest Way to Make a Simple Enemy AI in Unreal Engine 5) I used this example to help finish my enemy AI by adding the ability for the enemy to be able to see the player, and then follow them and damage them. 

(How To Make Wall Jump and Slide In Unreal Engine 5) I used this to help with getting the character to wall jump as well as stick to the walls that are wall jump-able to allow the player the room to react and jump off onto the next wall. With this I was also able to make it a function that any wall can be in the editor menu changed to allow the player to wall jump against it.


