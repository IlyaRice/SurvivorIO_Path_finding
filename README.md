# Game Pathfinding Project

## Overview
This project explores a pathfinding algorithm for a simulated game environment. The main goal of the project is to demonstrate the ability to apply programming and problem-solving skills to a defined context, simulating a real-world application.

## Game Rules

<table>
<tr>
<td>

The game is played on a 7x9 grid where a character starts in the middle of the field and has to complete exactly 15 steps without revisiting any cell or stepping out of the grid boundaries. The cells can be empty or contain prizes with different values (1, 2, or 3). The aim is to collect as many points as possible without reaching a dead end. If the path reaches a dead end (i.e., no further steps can be taken without breaking the rules), it is considered incomplete and non-viable.

### Specific Rules:
- The character starts at the center of the field.
- Each move can be up, down, left, or right.
- Stepping on an already visited cell is not allowed.
- The path must be exactly 15 steps long.

</td>
<td>

<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/00%20initial%20field.png" width="100%">

</td>
</tr>
</table>


## Code Description
This project includes several Python scripts encapsulated in a Jupyter Notebook that:
- Load and preprocess game field screenshots to categorize cells based on potential rewards using color analysis.
- Utilize a depth-first search (DFS) algorithm to explore all possible paths that collect prizes within the constraints of the game.
- Visualize the game field, the paths taken, and analyze the paths to determine the most and least effective strategies.

## Goals
The main objectives of this project were:
- To gain hands-on experience with Python and libraries such as NumPy, Matplotlib, and PIL.
- To understand and implement a recursive pathfinding algorithm.
- To prectice data visualization skills by plotting the results of the algorithm.

## Project Status
This project is currently in a prototype stage. It serves as a demonstration of my current skills and understanding in Python coding, algorithms, and data visualization. Further development may be undertaken to refine the code and expand its functionality.

## Visual Demonstrations
Here are some images that demonstrate various aspects and outputs of the project:

### Initial Field
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/00%20initial%20field.png" width="40%">

### Initial Field (Cropped)
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/01%20Initial%20field(cropped).png" width="40%">

### Recognized and Visualized Field
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/02%20Recognized%20and%20visualized%20field.png" width="40%">

### Priority Path (3 Score)
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/03%203%20score%20priority%20path.png" width="40%">

### Priority Path (2 Score)
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/04%202%20score%20priority%20path.png" width="40%">

### Priority Path (1 Score)
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/05%201%20score%20priority%20path.png" width="40%">

### Most Valuable Path
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/06%20most%20valuable%20path.png" width="40%">

### Least Valuable Path
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/07%20least%20valuable%20path.png" width="40%">

### Path with Least Empty Cells
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/08%20least%20empty%20cells%20path.png" width="40%">

### Field Usage Visualization
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/09%20field%20usage%20visualization.png" width="40%">

### Field Usage for Paths with Different Points Amount
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/10%20field%20usage%20for%20paths%20with%20different%20points%20amount.gif" width="40%">

### Dependency of the Amount of Paths on Points Collected
<img src="https://raw.githubusercontent.com/IlyaRice/SurvivorIO_Path_finding/master/Outputs/11%20dependency%20of%20the%20amount%20of%20paths%20on%20points%20collected.png" width="80%">

## Usage
To run this project, ensure you have Jupyter Notebook installed with Python 3, and the necessary libraries (NumPy, Matplotlib, and PIL). Open the notebook and execute the cells sequentially to see the pathfinding in action and visualize the results.
