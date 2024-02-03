Dots and Boxes Game
This is a simple implementation of the Dots and Boxes game in C++. Players take turns connecting dots to form lines, and when a player completes a box, they earn a point. The player with the most points at the end wins.

How to Play
1. Run the program.
2. Enter the player names.
3. Players take turns choosing either a horizontal or vertical line to connect dots.
4. The game continues until all boxes are formed.
5. The player with the most points at the end wins.

Features
- Two players can play the game.
- Players can choose either horizontal or vertical lines.
- The program keeps track of each player's score.

Code Structure
The code is structured into functions for different tasks:

- `print()`: Prints the current state of the game board.
- `player1()`: Handles the turn for Player 1.
- `player2()`: Handles the turn for Player 2.

How to Compile
Compile the program using a C++ compiler. For example:

`bash
g++ dots_and_boxes.cpp -o dots_and_boxes
