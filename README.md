# Tic-Tac-Toe

This project is a simple Tic Tac Toe game built with HTML, CSS, and JavaScript. It allows two players to play alternately, keeps track of turns, and announces the winner or a draw. This project demonstrates fundamental concepts of web development and DOM manipulation.

**Features**

Two-Player Gameplay: Supports two players (Player O and Player X) taking alternate turns.

Winner Detection: Automatically detects the winner based on the standard Tic Tac Toe rules.

Draw Detection: Declares a draw if all boxes are filled without a winner.

Interactive UI: Players can see the turn reflected immediately on the game board.

**Game Controls:**

Reset Game: Resets the game to its initial state.

New Game: Starts a fresh game.

Responsive Design: The game is designed to work on various screen sizes.

**Technologies Used**

HTML: Structure of the game and elements.

CSS: Styling and layout of the game board and controls.

JavaScript: Core logic for game functionality.

**File Structure**

├── index.html    # The main HTML structure
├── style.css     # Styling for the game
├── app.js        # Game logic and interactivity

**How to Use**

Clone or download the repository.

Open index.html in your web browser to play the game.

Follow these steps to play:

Players take turns clicking on empty boxes.

The first player to align three of their symbols (horizontally, vertically, or diagonally) wins.

If all boxes are filled and no player has aligned three symbols, the game declares a draw.

Use the Reset Game button to reset the current game.

Use the New Game button to start a fresh game.

**Game Logic**

Turn Tracking: The turnO variable tracks whose turn it is (true for Player O, false for Player X).

Winner Detection: The checkWinner() function checks if any of the predefined win patterns matches the board's current state.

Draw Detection: If all boxes are filled and no winner is found, the game declares a draw using the gameDraw() function.

Box Interaction: Players can click on a box to mark it with their symbol. Boxes are disabled after being clicked.

**Code Overview**

**CSS Styling**

The game board is styled using the .game and .box classes.

Buttons and messages are styled for a clean and simple UI.

The .hide class is used to show/hide the winner message.

**JavaScript Functions**

resetGame: Resets the board and game state.

gameDraw: Displays a draw message and disables the board.

disableBoxes: Disables all game boxes to prevent further clicks.

enableBoxes: Enables all game boxes and clears their content.

showWinner: Displays the winner message and disables the board.

checkWinner: Checks the board for a winner using predefined patterns.

**Event Listeners**

Box Clicks: Updates the box with the player's symbol, disables it, and checks for a winner or draw.

New Game & Reset Buttons: Resets the game board and state when clicked.

**Future Enhancements**

Add an option for single-player mode with an AI opponent.

Include a scoreboard to keep track of wins and draws.

Add animations for winning patterns or transitions.

Improve accessibility and mobile responsiveness.

**License**

This project is open-source and available under the MIT License.
