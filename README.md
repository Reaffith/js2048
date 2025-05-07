
# 2048 Game

## Description

2048 is a single-player sliding tile puzzle game where the objective is to combine tiles with the same numbers to create a tile with the value of 2048. The game is played on a 4x4 grid, and players can move tiles in four directions (up, down, left, right) using arrow keys. Each move may cause a new tile (with a value of 2 or 4) to appear on the board. The game ends when the player either achieves the 2048 tile (win) or cannot make any more moves (lose).

## Live Preview

[https://reaffith.github.io/js2048/](https://reaffith.github.io/js2048/)

## Technologies Used

- **HTML5**: For structuring the game interface.
- **SCSS/SASS**: For styling the game with modular and maintainable CSS, following the BEM (Block, Element, Modifier) methodology for consistent naming conventions.
- **JavaScript**: For game logic, including tile movements, score tracking, and game state management.
- **Node.js**: For managing dependencies and running the development server.
- **Git**: For version control.

## Getting Started

Follow these instructions to set up and run the project locally:

### Clone the Repository

```bash
git clone https://github.com/Reaffith/js2048.git
cd 2048-game
```

### Install Dependencies

Ensure you have Node.js (version 18.x or higher) installed. Then run:

```bash
npm install
```

### Run the Project Locally

Start the development server:

```bash
npm start
```

The project should now be running at [http://localhost:3000](http://localhost:3000).

## Features

- **Interactive Gameplay**: Use arrow keys to slide tiles and combine matching numbers.
- **Score Tracking**: Displays the player's score as tiles are combined.
- **Game Status Messages**: Notifies players when they win, lose, or need to start the game.
- **Restart Functionality**: Allows players to restart the game at any time.

