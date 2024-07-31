# HeliHurdles<br>
A side-scrolling helicopter game built with Python and Pygame.<br>

## Description<br>
This project is a simple yet engaging helicopter game where the player navigates through procedurally generated terrain. The game features increasing difficulty, score tracking, and dynamic visual changes based on the player's score.<br>

## Features<br>
- Procedurally generated terrain
- Gravity-based player movement
- Increasing difficulty as the game progresses
- Score tracking with high score system
- Dynamic color changes based on score
- Simple, intuitive controls

## Requirements<br>
- Python 3.x
- Pygame

## Installation<br>
1. Clone this repository
2. Install Pygame: `pip install pygame`
3. Run the game: `python helicopter_game.py`

## How to Play<br>
- Press SPACE to make the helicopter ascend
- Release SPACE to descend
- Navigate through the terrain without colliding
- Press ENTER to restart after a game over

## Code Structure<br>
The game is built using several key functions:
- `generate_new()`: Creates the initial game map
- `draw_map()`: Renders the terrain
- `draw_player()`: Renders the player's helicopter
- `move_player()`: Handles player movement
- `move_rects()`: Scrolls the terrain
- `check_collisions()`: Detects collisions between the player and terrain
  
## Tutorial Reference<br>
This project was created following the tutorial by LEMaster Tech. You can find the original tutorial here:
[LeMaster Tech's Helicopter Game Tutorial](https://youtu.be/W-3okcjOFnY?si=MP-eqPUAQMsHIks0)

## Future Improvements<br>
- Add sound effects and background music
- Implement power-ups and obstacles
- Create multiple levels or game modes
- Optimize performance for smoother gameplay



