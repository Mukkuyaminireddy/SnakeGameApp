# SnakeGameApp

This project is a classic Snake Game developed in Java using Swing for the graphical interface. The game consists of a snake that moves continuously on a board, eating food to grow in size while avoiding collisions with itself or the walls. The project demonstrates core object-oriented programming (OOP) principles and game loop logic, as well as event handling through user input.

Key Features:
Game Logic:

The snake starts as a small entity and grows each time it eats food. The game ends if the snake collides with itself or the edges of the board.
Movement is handled by adjusting the snake's head position and updating the body to follow.
Graphical Interface:

The game uses JPanel to draw the grid, snake, and food. The paintComponent() method is overridden for custom drawing.
The snake and food are drawn as colored ovals.
User Input & Control:

Keyboard inputs (arrow keys) are used to control the direction of the snake via the KeyListener interface.
The game loop is maintained by a Timer, which calls the actionPerformed() method to update the game state at regular intervals (100 ms).
Randomization:

The position of the food is randomized using Java’s Random class, ensuring the food appears at different locations each time.
Game Over & Score:

The game ends when the snake hits the boundary or its own body, and the final score (snake's length) is displayed.
Technologies Used:
Java for the core programming language.
Swing for graphical rendering and handling user interaction.
OOP Concepts: Classes, objects, inheritance (from JPanel), and encapsulation of game entities like snake and food.
