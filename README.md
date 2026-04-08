# 15-Puzzle Game

A classic sliding puzzle game built with HTML, CSS, and plain JavaScript. The objective of the game is to arrange the numbered tiles in sequential order (from 1 to 15) from top-left to bottom-right, leaving the bottom-right corner empty.

## Features

- **User System:** Players can enter their name before starting the game to track their performance.
- **Move Counter:** Keeps track of how many moves you have made during the game.
- **Timer:** Records the time taken to solve the puzzle.
- **Leaderboard:** Displays a ranking of players based on their lowest moves and best solving time.
- **Win State:** Congratulates the player upon successfully arranging all tiles in the correct sequence.

## Technologies Used

- **HTML5:** Structure of the game pages (Login, Game board, Leaderboard).
- **CSS3:** Styling and layout of the puzzle and interface.
- **JavaScript (ES6):** Game logic, shuffling algorithm, timer, DOM manipulation, and leaderboard management.

## How to Play

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Enter your name in the login screen.
4. Click on any tile adjacent to the empty space to slide it into the empty spot.
5. You can also use the Arrow keys on your keyboard to slide tiles (if supported).
6. Try to order the numbers from 1 to 15 in the fewest moves and shortest time possible!

## Project Structure

- `index.html`: The main HTML layout containing the login, game board, and leaderboard sections.
- `style.css`: The stylesheet that handles the look and feel of the puzzle tiles and text.
- `script.js`: The central script handling game interactions, shuffling, move counting, and timer mechanics.
