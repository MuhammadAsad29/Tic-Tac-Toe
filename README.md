# Tic Tac Toe

A simple Java Swing implementation of the classic Tic Tac Toe game. The project provides a graphical user interface with a 3×3 grid of buttons, alternating players (X and O), win/draw detection, and basic game state management.

## Overview

This repository contains a standalone Java application that uses Swing for rendering the game board. The main class creates a 3×3 button grid, handles player moves, checks for win conditions, and identifies draws. The GUI displays the current player's moves on the board and prevents further moves after the game concludes.

## Features

- Graphical user interface using Java Swing.
- 3×3 board with clickable buttons.
- Two-player alternating turns (X and O).
- Win detection across rows, columns, and diagonals.
- Draw detection when the board is full with no winner.
- Simple internal state management for game activity and player turns.

## Project structure

```
TicTacToe/
├─ src/
│  └─ TicTacToe.java        # Main Java source (Swing GUI and game logic)
├─ out/production/TicTacToe/          # Compiled class artifacts (IDE build output)
│  └─ TicTacToe.class
├─ .idea/                   # IDE project files (IntelliJ IDEA metadata)
└─ TicTacToe.iml            # IntelliJ module file
```

## Built with

- Java (Swing)

## Requirements

- Java JDK 20 or higher
- IntelliJ IDEA (Community or Ultimate)
- (Optional) Maven or Gradle if projects use a build tool

## License & Author

```
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Author: Muhammad Asad
```
