# Game Pathfinding Project

## Overview
This project explores a pathfinding algorithm for a simulated game environment. The main goal of the project is to demonstrate the ability to apply programming and problem-solving skills to a defined context, simulating a real-world application.

## Game Rules
The game is played on a 7x9 grid where a character starts in the middle of the field and has to complete exactly 15 steps without revisiting any cell or stepping out of the grid boundaries. The cells can be empty or contain prizes with different values (1, 2, or 3). The aim is to collect as many points as possible without reaching a dead end. If the path reaches a dead end (i.e., no further steps can be taken without breaking the rules), it is considered incomplete and non-viable.

### Specific Rules:
- The character starts at the position (4,3).
- Each move can be up, down, left, or right.
- Stepping on an already visited cell is not allowed.
- The character cannot move outside the grid boundaries.
- The path must be exactly 15 steps long.

## Code Description
This project includes several Python scripts encapsulated in a Jupyter Notebook that:
- Load and preprocess game field images to categorize cells based on potential rewards using color analysis.
- Utilize a depth-first search (DFS) algorithm to explore all possible paths that collect prizes within the constraints of the game.
- Visualize the game field, the paths taken, and analyze the paths to determine the most and least effective strategies.

## Practical Applications
In practice, this project serves as a base for understanding how pathfinding algorithms can be applied in game development and other areas such as robotics and urban planning. The project uses visualizations to demonstrate the potential paths and strategies in a grid-based environment, making it easier to analyze the efficiency of different paths.

## Goals
The main objectives of this project were:
- To gain hands-on experience with Python and libraries such as NumPy, Matplotlib, and PIL.
- To understand and implement a pathfinding algorithm.
- To demonstrate data visualization skills by plotting the results of the algorithm.
- To develop problem-solving and debugging skills in a practical coding environment.

## Project Status
This project is currently in a prototype stage. It serves as a demonstration of my current skills and understanding in Python coding, algorithms, and data visualization. Further development may be undertaken to refine the code and expand its functionality.

## Usage
To run this project, ensure you have Jupyter Notebook installed with Python 3, and the necessary libraries (NumPy, Matplotlib, and PIL). Open the notebook and execute the cells sequentially to see the pathfinding in action and visualize the results.