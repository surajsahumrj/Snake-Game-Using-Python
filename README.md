# Snake Game

This is a simple implementation of the classic Snake game using Python and the Pygame library. In this game, the player controls a snake that moves around the screen to eat food. The snake grows longer with each piece of food it eats, and the game ends when the snake hits the boundaries of the screen or itself.

## Features

- **Snake movement:** Use the arrow keys to move the snake in four directions: up, down, left, and right.
- **Growing snake:** Every time the snake eats food, it grows longer.
- **Score:** The score increases as the snake eats food, and the score is displayed on the top-left corner of the screen.
- **Game Over:** The game ends when the snake collides with the wall or itself.
- **Restart or Quit:** After losing, the player can press 'C' to play again or 'Q' to quit the game.

## Installation

1. **Install Python:** Ensure Python is installed on your computer. If not, you can download and install it from [here](https://www.python.org/downloads/).

2. **Install Pygame:** You can install Pygame using pip:
   ```bash
   pip install pygame
   ```

3. **Clone the Repository:** If you're working with a local repository, clone it to your machine or download the `snake_game.py` file.

4. **Run the Game:** Open a terminal, navigate to the directory containing the script, and run it:
   ```bash
   python snake_game.py
   ```

## Controls

- **Arrow Keys:** Move the snake in four directions (Up, Down, Left, Right).
- **C:** Play again after losing.
- **Q:** Quit the game.

## Code Explanation

- **Main Loop:** The game runs inside the `gameLoop()` function. The snake is controlled by changing its position based on the arrow key inputs. The game will continue running until the snake either collides with a wall or itself.
- **Game Over:** When the game ends, the player is given the option to restart by pressing 'C' or quit by pressing 'Q'.
- **Food Generation:** Food is placed randomly on the screen, and when the snake eats it, the snake's length increases, and new food appears.

## Credits

- **Pygame:** This game uses the Pygame library for rendering graphics and handling game events.
