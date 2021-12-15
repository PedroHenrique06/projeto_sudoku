# Intro

This project implements a terminal version of the Sudoku game.

# The game

According to the [wikipedia](https://en.wikipedia.org/wiki/Sudoku):

> Sudoku is a logic-based, combinatorial number-placement puzzle.
> The objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid (also called "boxes", "blocks", or "regions") contain all of the digits from 1 to 9.
> The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

The Sudoku rules are:

1. Each row, column, and nonet can contain each number (typically 1 to 9) exactly once.
2. The sum of all numbers in any nonet, row, or column must be equal to 45.

# Input

Puzzles are read, by default, from `data/input.txt`.

# Usage

```
% ./sudoku --help
Usage: sudoku [<options>] [<input_cfg_file>]
  Game options:
    --ncheck  <num> Number of checks per game. Default = 3.
    --help          Print this help text.
```

# Features

The game offers:

+ colored output.
+ indication of _invalid_ plays, i.e. plays that breaks the Sudoku's basic rules.
+ a simple interface.
+ undo actions.
+ limited possibility of checking if a move is correct or not.

# Author

UFRN/DIMAp, copyright 2020.

Selan R. dos Santos
