Snake Game 🐍


This is a simple Snake Game built using Python and the Turtle graphics library. The game features a snake that moves around the screen, collects food to grow, and keeps track of the score. The objective is to collect as much food as possible without colliding with the walls or the snake's own tail.

Features

Responsive Snake Movement: The snake moves up, down, left, or right based on the player's input.
Food Collection: The snake grows and the score increases whenever it eats the food.
Game Over: The game ends if the snake collides with the wall or with its own tail.
Scoreboard: Displays the current score at the top of the screen.

How to Play

Use the arrow keys to move the snake:
Up Arrow: Move up
Down Arrow: Move down
Left Arrow: Move left
Right Arrow: Move right
Collect the food (blue circle) to grow the snake and increase your score.
Avoid running into the walls or your own tail. If this happens, the game will display "GAME OVER."


Project Structure

├── snake.py           # Contains the Snake class responsible for snake movements
├── food.py            # Contains the Food class responsible for food appearance and refresh logic
├── scoreboard.py      # Contains the Scoreboard class to manage and display the score
├── main.py            # Main file to start the game and handle game logic
├── README.md          # This file


Prerequisites

Python 3.x
turtle library (pre-installed with Python)
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/snake-game.git
Navigate to the project directory:

bash
Copy code
cd snake-game
Run the game:

bash
Copy code
python main.py

Future Enhancements

Add levels with increasing difficulty.
Include sound effects when the snake eats food or hits the wall.
Implement a pause and resume functionality.
