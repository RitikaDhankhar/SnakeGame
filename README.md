# SnakeGame
The Snake Game is a classic arcade game that has been enjoyed by many generations. In this project, we will create a simple version of the Snake Game using Python and the tkinter library.
**Objective**
The objective of the Snake Game is to control a snake and navigate it to eat food. Each time the snake eats food, it grows longer, making the game progressively more challenging. The game ends if the snake collides with itself or the walls.
**Game Components**
**Snake**: A series of connected segments that move together in the direction specified by the player. The snake initially starts with a small number of segments and grows longer as it eats food.

**Food**: A single piece of food that appears at random locations on the screen. When the snake eats the food, it grows by one segment, and a new piece of food appears at a different random location.

**Key Functions and Classes**

**Game Initialization:**
Set up the game window, initialize Pygame, and set up game variables (e.g., snake position, food position, score).

**Snake Movement:**
Update the position of the snake based on user input.
Move the snake by adding a new segment in the direction of movement and removing the last segment if the snake hasn't eaten food.

**Collision Detection:**
Check for collisions with the walls or self-collision (when the snake runs into its own body).
End the game if a collision is detected.

**Food Generation:**
Place the food at random locations on the screen.
Ensure the food does not appear on the snake's body.

**Game Loop:**
Continuously update the game state: handle user input, move the snake, check for collisions, and update the display.
Maintain a consistent frame rate for smooth gameplay.

**Game Over:**
Display a game over message when the snake collides with the wall or itself.

![image](https://github.com/Ritika12-prog/SnakeGame/assets/68142518/651c8da4-1d77-45d4-ac46-28473c7955c3)



![image](https://github.com/Ritika12-prog/SnakeGame/assets/68142518/6203c52e-5aea-40a6-be44-97a2f140cd6c)
