# Knight Battle

A game created in my Introduction to Programming course. 

During my undergraduate career, I had to create a game as a final project to my class. To create a cumulative list of what was learned during this time, specific base topics in object-oriented programming are conceptualized in a visual game format. 

The game starts off with a Start Screen. Players are introduced to the components of the gameplay through interaction of the keyboard. 

![alt-text](/images/start-screen.png)

The game is played by a Single-Player in a turn-based format. Once the game is initialized, the player starts off in the center of the world and is encouraged to explore as much as possible and interact with other NPCs. The concept of this component of the game was to understand player movement and directional orientation on a computer screen through the W-A-S-D commands. A sprite sheet was utilized to cycle through an array of images and correctly identify which of the sprites would be correlated with the direction of the player.
![alt-text](/images/start-game.png)

The game also allowed the player to note the reference to their location through the use of a minimap, displaying the X and Y coordinates of the player relative to the screen size. 
![alt-text](/images/minimap.png)

Once the player was within a certain radius of an enemy, this prompted the enemy to move within a distance to the player that prompted the next scene of the turn-based game to occur. If the player wins the battle, the enemy is removed from the game and the player is awarded an increase in stats, such as Attack, Defense, and Experience. Furthermore, their health is also impacted and can be viewed on the top of the screen. 
![alt-text](/images/battle-lvl-1.png)
![alt-text](/images/attack-defense-exp.png)
The player can also lose the battle, which results in the player losing health and the enemy remaining in the game. If the player loses, they lose a heart and are reset to the center of the screen in the grid-level map to ensure they are away from the enemy and no constant loop of battling occurs. 

If the player finds they must recover health, the player can also interact with the NPC that is a healer. 
![alt-text](/images/healing.png)
The player can also interact with other NPCs that are not enemies to give them hints into thes storyline of the gameplay. 
![alt-text](/images/interaction.png)

As the player progresses and strengthens through the game, the enemies become stronger and more difficult to defeat. 
![alt-text](/images/battle-lvl-2.png)

A border system was set in place to ensure the player doesn't battle an enemy that is too strong for them. Once the player defeats all of the enemies on the island, they should be strong enough for the final boss.
![alt-text](/images/border-and-health.png)
![alt-text](/images/final-boss.png)

The game ends with a time score that overwrites if the previous record is broken:
![alt-text](/images/high-score.png)

All of the concepts in this game were learned through the course of the semester to introduce fundamentals in programming and Object-Orientation. 