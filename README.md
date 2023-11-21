Space Shooter Game
Overview
This Python code is a simple implementation of a space shooter game using the Pygame library. The game features a player-controlled spaceship that can move horizontally and vertically, shoot lasers, and has a health bar. The objective is to survive waves of enemy spaceships while avoiding collisions and enemy lasers.

Features
Player-controlled spaceship with movement in four directions (up, down, left, right).
Shooting lasers to destroy enemy spaceships.
Enemy spaceships with random colors (red, green, blue) and the ability to shoot lasers.
Health bar for the player, displayed at the bottom of the screen.
Lives counter to keep track of the player's remaining lives.
Levels that increase in difficulty with more enemy spaceships in each wave.
How to Play
Use the W, A, S, D keys to move the player spaceship (up, left, down, right).
Press the SPACEBAR to shoot lasers and destroy enemy spaceships.
Avoid collisions with enemy spaceships and their lasers.
The game ends when the player runs out of lives or health.
Installation
Ensure you have Python installed on your machine.
Install the Pygame library using the following command:
pip install pygame
Download the code and assets.
Run the script by executing the following command in the terminal:
python space_shooter.py
Assets
The game uses pixel art assets for spaceships, lasers, and the background. You can find these assets in the "assets" folder.

Player Spaceship: pixel_ship_yellow.png
Enemy Spaceships: pixel_ship_red_small.png, pixel_ship_green_small.png, pixel_ship_blue_small.png
Lasers: pixel_laser_yellow.png, pixel_laser_red.png, pixel_laser_green.png, pixel_laser_blue.png
Background: background-black.png
Code Structure
The code is organized into classes for the main elements of the game: Laser, Ship, Player, and Enemy.
Collision detection is implemented using masks to check for overlaps between objects.
The main function runs the game loop, handles player input, and manages enemy waves.
The main_menu function displays a simple menu to start the game.
Dependencies
Python 3.x
Pygame library
Credits
This code is a tutorial implementation and uses assets from an external source (not specified in the provided code).

License
This code is provided without a specific license. Please refer to the licenses of the included assets for more information.

Enjoy playing the space shooter game!
