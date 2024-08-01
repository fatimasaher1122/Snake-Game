# Snake-Game
Overview
This is a classic Snake game implemented in Java using Swing and AWT for graphical user interface (GUI) development. The game features a splash screen, gameplay with interactive controls, and a simple scoring system. The goal is to control the snake to eat apples and grow, while avoiding collisions with itself and the walls.

Features
Splash Screen: Displays an animated introduction with a "Start Game" button.
Game Panel: The main game interface where the Snake moves, eats apples, and grows. Features include:
Snake Movement: Controlled by arrow keys.
Apple Generation: Apples appear at random positions on the screen.
Score Tracking: Displays the current score and the highest score achieved.
Game Over Screen: Shows the final score and highest score with an option to restart the game.
Components
GameFrame:

Splash: Displays the splash screen on application start.
GamePanel: Handles the main game logic, rendering, and user interactions.
GamePanel:

Constants: Defines game settings such as screen dimensions, unit size, and delay.
Game State: Manages the snake's position, apple's location, direction of movement, and game status.
Drawing: Renders the snake, apple, and score on the screen.
Game Mechanics: Includes methods for starting, moving, resetting the game, and handling collisions.
Splash:

Start Button: Allows users to start the game from the splash screen.
Background: Displays a background image and game title.
SnakeGame:

Main Class: Launches the game by creating an instance of GameFrame.
