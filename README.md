# Tic Tac Toe Game in React

## Overview

This is a simple Tic Tac Toe game built using React.js. The game allows two players to take turns marking spaces in a 3×3 grid, with the goal of getting three of their marks in a row to win.

## Features

- Interactive Tic Tac Toe board
- Player turn indicators
- Automatic win detection
- Reset functionality to start a new game

## Technologies Used

- React.js
- CSS for styling
- useState and useRef hooks for state management

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-react.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tic-tac-toe-react
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Click on any empty box to make a move.
2. The game alternates turns between two players (X and O).
3. When a player gets three marks in a row, a winning message is displayed.
4. Click the "Reset" button to start a new game.

## Project Structure

```
├── src
│   ├── Assets
│   │   ├── circle.png
│   │   ├── cross.png
│   ├── Components
│   │   ├── TicTacToe
│   │   │   ├── TicTacToe.js
│   │   │   ├── TicTacToe.css
│   ├── App.js
│   ├── index.js
├── public
│   ├── index.html
├── package.json
├── README.md
```

## Future Improvements

- Add an AI opponent for single-player mode.
- Improve UI design and animations.
- Implement a scoreboard to track wins.

## Author

This project was developed by Mohamed Osama Elkhateeb.
