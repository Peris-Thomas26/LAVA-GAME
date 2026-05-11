# Lava Maze Game

A fast-paced maze game built with Python's Turtle graphics. Navigate a flooding maze, dodge rising lava, and collect gold coins before it's too late.

## About

You play as a bird (blue square) trapped in a 9x9 maze that is rapidly flooding with lava. Your goal is to collect all 4 gold coins scattered across the maze before the lava reaches you. Every move you make causes 4 more cells of lava to appear, so plan your route carefully.

## Features

- Grid-based maze with walls, gold coins, and rising lava
- Arrow key controls for real-time movement
- Lava that progressively floods the maze from the bottom-right corner
- Boundary and wall collision detection
- Win/lose conditions with on-screen messages

## How to Play

| Element        | Appearance   | Description                     |
|----------------|--------------|---------------------------------|
| Player         | Blue square  | You — move with arrow keys      |
| Gold           | Yellow square| Collect all 4 to win            |
| Wall           | Grey square  | Blocks movement                 |
| Lava           | Red square   | Instant death on contact        |
| Empty space    | White square | Safe to walk on                 |

**Controls:** Use the arrow keys (Up, Down, Left, Right) to move.

**Win:** Collect all 4 gold coins.

**Lose:** Touch the lava.

## Requirements

- Python 3.x
- No external libraries required (uses built-in `turtle` and `time` modules)

## How to Run

```bash
python "LAB 4 LAVA _GAME.py"
```

A window will appear with instructions. After a few seconds the maze loads and you can start playing.

## Author

**LYIMO Peris Thomas** — SID: 21145542
