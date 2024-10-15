# Tic-Tac-Toe 2.0

## Description
This is a simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game allows two players to play against each other in turns, and it automatically detects the winner based on predefined winning patterns.

## How to Play
- Two players take turns to mark the boxes with `0` or `X`.
- The first player to align three symbols in a row, column, or diagonal wins the game.
- Once a player wins, the game disables further moves and displays the winner.
- You can reset the game or start a new game anytime by clicking the **Reset** or **New Game** buttons.

## Features
- Two-player support with alternating turns.
- Automatic detection of winning patterns.
- Reset and New Game functionality to restart the game.
- Visual indicator of the winner.

## Installation
To run the game locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone [https://github.com/Deepti-mayee/Tic-tac-toe.git]
   ```
2. Navigate to the project directory:
   ```bash
   cd Tic-tac-toe
   ```
3. Open `index.html` in your web browser to start playing.

## Files
- `index.html`: Contains the game layout.
- `style.css`: Contains the styling for the game board and messages.
- `app.js`: The JavaScript logic to handle player moves, detect winners, and manage game state.

## Usage
1. Open the game and click on any box to make your move.
2. The game alternates turns between `0` and `X`.
3. The game will automatically check for a winner after each move.
4. To start a new game, click the **New Game** or **Reset** button.

## Code Breakdown
### Main Logic
- The game listens for clicks on each box. Once clicked, the box is marked with either `0` or `X` based on the current player's turn.
- The `checkForWin` function checks the board against predefined winning patterns.
- If a player wins, the board is disabled and a message is shown.
  
### Game Controls
- **Reset**: Clears the board and resets the turn to the starting player (`0`).
- **New Game**: Same functionality as Reset.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

## Contact
For any questions or feedback, reach out via [deeptimayee1112@gmail.com].
