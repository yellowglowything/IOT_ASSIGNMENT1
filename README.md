# IOT_ASSIGNMENT1
## IOT ASSIGNMENT1 SUBMISSION : Microbit Game
<br />Made with Microbit Python
<br />This is a shooter game,  the objective is to shoot as many enemies as possible. The more enemies defeated, the higher the score. The game ends when an enemy touched the player.
## HOW TO PLAY 
### How to open
<br />To play the game, first go to Microbit Python editor site and create a new project. This link will take you there https://python.microbit.org/v/3
<br />Next click open a file, and choose the hex file that is inside this project
### Controls
<br />The player sprite is spawned at the bottom middle of the screen
<br />he enemy sprites are generated in a formation at the top end of the screen. The formations are randomized at every wave.
<br />To move, tilt the microbit left and right. The longer you tilt, the faster you move. It is game over if the enemy sprites touch you.
<br />To shoot, press button A. It will fire a missle that moves vertically. Once it hits an enemy, it dies. The wave is complete after all enemies in a formation is dead.
<br />For the Bomb, press button B. The explosion has a 50% chance of killing an enemy sprite. This is to say, each enemy in a formation will have a 50% chance of dieing with every bomb. Works better when there is a higher number on enemies present
<br />Score will be displayed after the player dies.
