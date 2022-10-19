# Tic_Tac_Toe
Tic Tac Toe is one of the most played games and is the best time killer game that you can play anywhere with just a pen and paper. If you don’t know how to play this game don’t worry let us first understand that.

The game is played by two individuals. First, we draw a board with a 3×3 square grid. The first player chooses ‘X’ and draws it on any of the square grid, then it’s the chance of the second player to draw ‘O’ on the available spaces. Like this, the players draw ‘X’ and ‘O’ alternatively on the empty spaces until a player succeeds in drawing 3 consecutive marks either in the horizontal, vertical or diagonal way. Then the player wins the game otherwise the game draws when all spots are filled.

# Py Game

Pygame is a great library that will allow us to create the window and draw images and shapes on the window. This way we will capture mouse coordinates and identify the block where we need to mark ‘X’ or ‘O’. Then we will check if the user wins the game or not.

1. Create the display window for our game.
2. Draw the grid on the canvas where we will play Tic Tac Toe.
3. Draw the status bar below the canvas to show which player’s turn is it and who wins the game.
4. When someone wins the game or the game is a draw then we reset the game.

We shall run our game inside an infinite loop. It will continuously look for events and when a user presses the mouse button on the grid we will first get the X and Y coordinates of the mouse. Then we will check which square the user has clicked. Then we will draw the appropriate ‘X’ or ‘O’ image on the canvas.

# Summary

With this project in Python, we have successfully made the Tic Tac Toe game. We used the popular pygame library for rendering graphics on a display window. We learned how to capture events from the keyboard or mouse and trigger a function when the mouse button is pressed. This way we can calculate mouse position, draw X or O on the display and check if the player wins the game or not.