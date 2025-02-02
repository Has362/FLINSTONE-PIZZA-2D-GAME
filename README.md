# Flinstone Pizza 2D Game

This is a 2D side-scrolling game called "Flinstone Pizza" developed using Pygame. The player controls a dino character and must navigate through various levels, avoiding obstacles like rocks, shells, pitfalls, and traps to deliver pizza.

## Table of Contents

- [Gameplay](#gameplay)
- [Features](#features)
- [Installation](#installation)
- [Controls](#controls)
- [Levels](#levels)
- [Obstacles](#obstacles)
- [Sound](#sound)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Credits](#credits)

## Gameplay

The player controls a dino and runs from left to right. The dino can jump to avoid obstacles. The goal is to reach the end of each level without colliding with obstacles.  Colliding with an obstacle results in restarting the current level. Completing all levels leads to a "Game Completed" screen.

## Features

- **Multiple Levels:** The game features multiple levels, each with unique backgrounds and obstacles.
- **Obstacle Avoidance:** Players must avoid various obstacles, including rocks, shells, pitfalls, log traps, cat traps, water pitfalls and a Barney trap.
- **Jumping:** The dino can jump to avoid obstacles.
- **Sound Effects:**  The game includes jump and losing sound effects, as well as background music.
- **Level Transitions:**  The game seamlessly transitions between levels.
- **Game Completion:** A "Game Completed" screen is displayed upon successful completion of all levels.
- **Intro Video and Image:** The game starts with a short intro video followed by a static image before the main gameplay begins.

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[your-github-username]/FLINSTONE-PIZZA-2D-GAME.git  # Replace with your repo URL

2. **Install dependencies:**
   ```bash
   pip install pygame opencv-python numpy

3. **Place Assets:**

   Ensure all image and sound files are placed in the correct directories as specified in the code.  The code assumes a specific directory structure (e.g., img/, sounds/, 
   start_vid/).  Adjust the file paths in the code if necessary.

   A suggested structure is:

   FLINSTONE-PIZZA-2D-GAME/

   ├── img/  
   │   ├── background/  
   │   ├── clouds/  
   │   ├── Obstacles/  
   │   └── sprites/
   │       └── dino/
   │       └── Barney/
   ├── sounds/
   │   ├── jump.wav
   │   ├── losing.wav
   │   └── playing music.mp3
   └── start_vid/
       ├── 1.mp4
       └── gaaa.jpg
   └── FLINSTONE-PIZZA-2D-GAME.py
   └── README.md


## Controls

Left Arrow Key: Move left
Right Arrow Key: Move right
Spacebar/Up Arrow Key: Jump

## Levels

The game includes the following levels:

Level 1: Basic level
Level 2: Rocks as obstacles
Level 3: Shells as obstacles
Level 4: Pitfalls as obstacles
Level 5: Begining of the Forest
Level 6: Log and cat traps
Level 7: Water pitfalls
Level 8: Barney trap

## Obstacles

Rocks: Static obstacles in level 2.
Shells: Static obstacles in level 3.
Pitfalls: Gaps in the ground in level 4.
Log Trap: A trap in level 6.
Cat Trap: A trap in level 6.
Water Pitfalls: Gaps filled with water in level 7.
Barney: A character in level 8 that ends the game.

## Sound

Jump Sound: Played when the dino jumps.
Losing Sound: Played when the dino hits an obstacle.
Background Music: Plays continuously during gameplay.

## Dependencies

Pygame
OpenCV (cv2)
NumPy

## How to Run

Navigate to the game directory in your terminal.
Run the main Python file:
Bash

python FLINSTONE-PIZZA-2D-GAME.py

## Credits
This game was developed by - [Hasini Liyanawadu] - 
                             [Dewmini Apsara] -   
                             [Pavan Pramod] - 
                             [Vidun Tharumika] - 
                             
All the image assets including backgrounds, Obstacles were created by our selves.

Graphic Part - Pavan Pramod and Dewmini Apsara
Coding Part - Hasini Liyanawadu and Vidun Tharumika
