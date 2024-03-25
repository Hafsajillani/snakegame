#Snake Game Description
This project implements a classic snake game using HTML, CSS, and JavaScript. Here's a breakdown of its key features and functionalities:

#Game Elements
Draw Function: The draw function redraws the game board whenever the game state changes. It clears the board and then draws the snake and food using drawSnake and drawFood functions, respectively. The score display is also updated using updateScore.

##Move Function: The move function moves the snake based on the current direction. It calculates the new head position, adds it to the snake array, and removes the last segment of the snake if it hasn't eaten food. If the snake eats food, a new food is generated, and the game speed is increased.

##Collision Detection: The checkCollision function detects collisions with walls or itself. If a collision is detected, the resetGame function is called to reset the game.

#User Interaction
##Key Press Handling: The handleKeyPress function listens for key presses. Pressing the spacebar starts the game, while arrow keys change the direction of the snake.
Scoring and Game Over
##Score Tracking: The updateScore function calculates and updates the current score based on the snake's length. The high score is also updated in the updateHighScore function.

##Game Reset: When the game is over, the resetGame function resets the game state, including the snake, food, direction, and game speed. It also updates the high score if necessary.

#Game Start and Speed Increase
##Game Start: The startGame function hides the instruction text and logo, sets the gameStarted flag to true, and starts the game loop.

##Speed Increase: The increaseSpeed function decreases the gameSpeedDelay variable as the snake grows longer, increasing the game's speed.

#Display
##HTML Structure: The HTML structure defines the layout of the game board, scores, instruction text, and logo.

##CSS Styling: The CSS styles define the visual appearance of these elements, including colors, borders, fonts, and positioning.

This snake game project demonstrates the use of HTML, CSS, and JavaScript to create an interactive and engaging game. Enjoy playing!

---
