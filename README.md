# Snake Game

A simple Snake Game built using Python and the Pygame library. Control the snake, eat the food, and try to achieve the highest score without colliding with the walls or the snake's own body.



## Features
- **Dynamic Gameplay**: The snake grows in length as it eats the food.
- **Collision Detection**: The game ends if the snake collides with the walls or itself.
- **Custom Borders**: Added decorative yellow borders around the frame.
- **Scoring System**: Displays the player's score in real-time.



## How to Play
1. Run the game script using Python.
2. Use the arrow keys to control the snake's direction:
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
3. Eat the blue food to grow the snake and increase your score.
4. Avoid colliding with the walls or the snake's body.
5. If you lose, press **Q** to quit or **C** to restart the game.



## Controls
- **Arrow Keys**: Move the snake.
- **Q**: Quit the game.
- **C**: Restart the game after losing.



## Requirements
- Python 3.x
- Pygame library

To install Pygame, run the following command:
```bash
pip install pygame
```



## Code Overview
### Key Functions
- **`our_snake(snake_block, snake_list)`**: Renders the snake on the screen.
- **`message(msg, color)`**: Displays a message on the screen.
- **`gameLoop()`**: Contains the main game logic, including player input, collision detection, and rendering.

### Main Highlights
- The game screen is dynamically updated at a speed of 12 frames per second (modifiable).
- Food placement is randomized, ensuring new positions each time food is eaten.
- A border surrounds the game area, enhancing the visual appeal.



## Running the Game
1. Clone or download this repository.
2. Navigate to the project directory.
3. Run the script using the following command:
   ```bash
   python snake_game.py
   ```

## Acknowledgements
- Built with 💻 and 🎮 by Python and Pygame.
- Inspired by the classic Snake game (NoKia).
