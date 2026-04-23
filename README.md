# Minesweeper

A classic Minesweeper game implementation in Java using Swing GUI. Navigate a 10x10 grid, uncover tiles, and avoid the mines!

## Requirements

- Java 8 or higher

## How to Play

1. **Compile the project:**
   ```bash
   javac *.java
   ```

2. **Run the game:**
   ```bash
   java App
   ```

## Game Rules

- **Left Click**: Uncover a tile
  - If a tile contains a mine, the game ends and all mines are revealed
  - If a tile is safe, a number appears showing adjacent mine count
  - If no adjacent mines exist, the tile becomes blank and nearby tiles auto-reveal

- **Right Click**: Flag a tile as a suspected mine with a 🚩

## Game Objective

Uncover all safe tiles without hitting any mines. Win by clicking on all non-mine tiles!
