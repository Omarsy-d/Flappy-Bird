# FLAPPY BIRD
Flappy Bird created using Python and Pygame.

## Table of contents
+ Introduction
+ Features
+ Installation
+ How to Play
+ Game Assets
+ Code Structure

### Introduction
This is a Python and Pygame-based version of the popular game Flappy Bird. Players control a bird that flys and goes through pipes to earn points without hitting obstacles or falling to the ground.

### Features
+ Animation and physics
+ Randomly generated pipes for every new game
+ Score tracking
+ Restart button
+ Collision with ground, pipes, top border

### Instalation
1. Clone the repository
`git clone <repository_url>`
2. Navigate to the project directory
`cd FlappyBird`
3. Install the required dependencies: Make sure you have Python installed. Then, install Pygame using:
`pip install pygame`

### How to play
+ Run the game with the following command:
`python <your_script_name>.py`
+ Left click to make the bird jump.
+ Avoid hitting the pipes or the ground or top border.
+ When you hit a pipe or the ground, the game will end. Press the restart button to play again.

### Game assets
Make sure the following images are in the same directory as your code, or update the paths accordingly:
+ `background2.png`-Background image
+ `ground.png` - Ground image
+ `restart.png` - Restart button image
+ `birdie1.png`, `birdie2.png`, `birdie3.png` - Bird animation frames
+ `pipe.png` - Pipe image

### Code structure
**Bird Class:** Handles bird animation, movement, and collision detection.
**Pipe Class:** Handles the generation and movement of pipes.
**Button Class:** Creates a restart button that resets the game when clicked.
**Main Game Loop:** Handles games logic, including scrolling, score counting, collision detection, and drawing elements on the screen.



