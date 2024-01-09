# Week 2 Project Overview - Frog Leap Puzzle Game in Python

## Project Description
This project serves as an educational exercise in Python, focusing on implementing a classic 'Frog Leap' puzzle game. It's designed to be an engaging learning experience.

### Problem Statement
The goal is to create the famous 'Frog Leap' puzzle game where two sets of frogs (green and brown) need to switch positions based on specific movement rules.

### Rules
- The left set of frogs can only move right, while the right set of frogs can only move left.
- Frogs can move forward one space or leap two spaces by jumping over another frog from the opposite side.
- The puzzle is solved when the two sets of frogs have switched positions.

## Steps to Solve the Problem
### Step 1 - Initial Display
- Display green and brown frogs on the left and right sides initially.
- Example Initial Display: `[ 0 , 1 , 2 , 3 , 4 , 5 , 6 ] ['G', 'G', 'G', '-', 'B', 'B', 'B']`
  - 'G' represents Green frogs on the left side, 'B' represents brown frogs on the right side, and '-' defines the position of an empty leaf.

### Step 2 - Accept User Input for Frog Movement
- Accept positions of the frog that you want to move.
- Example: If the position entered is 2, the game will show: `[ 0 , 1 , 2 , 3 , 4 , 5 , 6 ] ['G', 'G', '-', 'G', 'B', 'B', 'B']`

### Step 3 - Define Invalid Moves
- Define rules for invalid moves using conditional 'if' statements:
  - Entered position should be between 0 to 6 or 'q' to quit the game.
  - The selected frog's position cannot be that of an empty leaf.
  - Ensure the move aligns with the constraints of the game.

### Step 4 - Update Game Display After Valid Moves
- Implement logic to update the game display based on valid moves made by changing the frog positions.

The project aims to create an interactive Python-based implementation of the 'Frog Leap' puzzle game, offering learning opportunities while having fun.
