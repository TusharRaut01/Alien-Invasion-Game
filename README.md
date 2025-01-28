Alien Invasion Game

Description

Alien Invasion is a 2D arcade-style game where the player controls a spaceship to defend Earth from waves of alien attacks. The objective is to shoot down as many alien ships as possible while avoiding getting hit. The game becomes progressively challenging as the aliens increase in number and speed.

Features

Player-controlled spaceship that can move left, right, and fire bullets.

Waves of alien ships that move horizontally and descend when they hit the screen edges.

Score system to track the player’s progress.

Levels that increase in difficulty as the game progresses.

Game Over when the player’s ship is hit or aliens reach the bottom of the screen.

Gameplay

Objective: Destroy all alien ships before they reach the bottom of the screen or destroy your spaceship.

Controls:

Arrow Keys: Move the spaceship left or right.

Spacebar: Shoot bullets.

Rules:

Each alien ship destroyed increases the score.

Survive as long as possible to achieve a high score.

Installation and Setup

Clone the repository:

git clone https://github.com/your-username/alien-invasion.git
cd alien-invasion

Install dependencies:
Ensure Python is installed on your system, along with the pygame library.

pip install pygame

Run the game:

python alien_invasion.py

Prerequisites

Python 3.6 or higher.

pygame library (install with pip install pygame).

Code Structure

alien_invasion.py: Main game logic.

settings.py: Configuration for game settings like screen size, colors, and speed.

ship.py: Code for the player-controlled spaceship.

alien.py: Code for alien ship behavior.

bullet.py: Code for bullets fired by the spaceship.

game_stats.py: Code to handle game statistics like scores and lives.

scoreboard.py: Display for score and other stats.

Future Improvements

Add power-ups for the spaceship.

Implement multiple spaceship designs.

Introduce new alien types with varied behaviors.

Add multiplayer mode.

Include background music and sound effects.
