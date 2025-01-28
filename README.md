# 15 Puzzle Game

## Overview
This project implements the classic 15 Puzzle (also known as Sliding Puzzle or Game of Fifteen) in C++. The game consists of a 4x4 grid with fifteen numbered squares and one empty space. Players can slide adjacent tiles into the empty space to rearrange the puzzle, with the goal of arranging the numbers in ascending order.

## Features
- Text-based user interface with clear board visualization
- Real-time move validation and error handling
- Move counter to track progress
- Board state validation to ensure solvability
- Save/load game functionality
- Option to generate random but solvable puzzle configurations
- Clear game instructions and help menu

## Topics Covered
- Dynamic memory allocation and management
- 2D array manipulation
- Object-oriented programming principles
- Class design and implementation
- File I/O operations
- Random number generation
- Game state management
- Input validation and error handling
- Algorithm implementation for puzzle solvability

## How to Play
1. The game starts with tiles 1-15 randomly arranged in a 4x4 grid, with one empty space
2. Use the following commands to move tiles:
   - W: Move tile above empty space down
   - S: Move tile below empty space up
   - A: Move tile to right of empty space left
   - D: Move tile to left of empty space right
3. Goal: Arrange the tiles in ascending order from left to right, top to bottom:
```
 1  2  3  4
 5  6  7  8
 9 10 11 12
13 14 15  _
```

## Requirements
- C++ compiler with C++11 support or later
- Standard Template Library (STL)
- Terminal/Console that supports ASCII output

## Game Commands
- WASD: Move tiles
- Q: Quit game
- R: Reset puzzle
- H: Display help
- S: Save game
- L: Load game

## Acknowledgments
- Based on the Learn C++ curriculum at learncpp.com
- Inspired by the classic 15 puzzle game invented by Noyes Palmer Chapman
