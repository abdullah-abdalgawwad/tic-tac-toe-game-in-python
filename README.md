# Tic Tac Toe Game

A simple command-line Tic Tac Toe game implemented in Python. This project demonstrates basic game logic and user interaction in a terminal-based interface.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Play](#how-to-play)
- [Game Logic](#game-logic)

## Project Overview

Tic Tac Toe is a two-player game where players take turns marking spaces in a 3x3 grid. The goal is to place three of your marks in a horizontal, vertical, or diagonal row. This implementation uses Python to handle the game logic and player input through the terminal.

## Features

- Two-player mode (player vs. player)
- Input validation to ensure valid moves
- Clear display of the game board after each move
- Detects win, lose, or draw conditions
- Option to restart the game after a match ends

## Technologies Used

- **Python**: The core programming language used for this project.
- **Command-Line Interface (CLI)**: For user interaction and display.

## How to Play

- The game is played on a 3x3 grid.
- Player 1 is X and Player 2 is O.
- Players take turns choosing a cell in the grid by entering the corresponding number (1-9).
- The first player to align three of their marks (X or O) in a row, column, or diagonal wins the game.
- If all cells are filled and no player has three in a row, the game ends in a draw.

  **Example of the Game Board**

   1 | 2 | 3 
   -----------
   4 | 5 | 6 
   -----------
   7 | 8 | 9 
 

## Game Logic

The game logic checks for the following conditions after each move:

- Win Condition: Checks if a player has placed three of their marks in a row, column, or diagonal.
- Draw Condition: If all cells are filled and no player has won, the game is declared a draw.
- Invalid Input Handling: Ensures that players do not enter invalid moves (e.g., a position that is already taken).


