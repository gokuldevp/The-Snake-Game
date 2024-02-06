# The Snake Game

## Introduction
This project is a simple implementation of the classic Snake game using the Turtle graphics library in Python. The game features a snake that grows longer as it eats food, and the player must control the snake's movements to avoid collisions with the snake's own body and the walls.

## Project Structure
The project is organized into several components:

1. **main.py:** The main script that sets up the game window, initializes the snake, food, scoreboard, and wall. It also contains the game loop and handles key events.

2. **wall.py:** Defines the Wall class, responsible for creating and displaying the boundaries of the game.

3. **snake.py:** Implements the Snake class, which represents the snake in the game. It handles the snake's movement, growth, and resetting.

4. **score.py:** Contains the Scoreboard class, which manages the player's score, high score, and updates the scoreboard on the screen.

5. **food.py:** Defines the Food class, responsible for creating and moving the food that the snake eats.

## How to Play
- Use the arrow keys to control the snake's direction: Up, Down, Left, and Right.
- The snake will continuously move in the current direction.
- Guide the snake to eat the green food to grow longer and earn points.
- Avoid collisions with the snake's own body and the walls.
- Press the 's' key to stop the game.

## Features
- The snake grows longer each time it eats food.
- The game keeps track of the player's score and the highest score achieved.
- The game stops if the snake collides with its own body or the walls.
- The high score is stored in a "Data.txt" file and updated after each game.

## How to Run
1. Ensure you have Python installed on your system.
2. Run the `main.py` script using a Python interpreter.
3. The game window will appear, and you can start playing.

## Dependencies
- Python 3.x
- Turtle graphics library
