# Shortest Path Finder using BFS

This is a Python program that implements a shortest path finder using the Breadth-First Search (BFS) algorithm. The program allows the user to draw obstacles and find the shortest path between a start point and an end point on a grid.

## Dependencies

The program requires the following dependencies:
- turtle
- tkinter

You can install these dependencies using pip:
```
pip install python-turtle
pip install tk
```

## How to Use

1. Run the program using Python.
2. A window titled "Finding the shortest path between two points" will appear.
3. The grid is displayed in the window. You can click on the grid to interact with it.
4. The following instructions are available:
   - Press 's' and click on the grid to set the starting point (color: green).
   - Press 'e' and click on the grid to set the ending point (color: blue).
   - Press 'h' and click on the grid to place hurdles (color: red).
   - Press 'r' to randomly generate hurdles on the grid.
   - Press the space bar to find and display the shortest path (colored in black).
   - Press 'o' to clear the grid and start over.

## Example Output

### Step 1

![Intial View](Images/Screenshot%20(3).png)

### Step 2

![Intial View](Images/Screenshot%20(4).png)
### Step 3

![Intial View](Images/Screenshot%20(5).png)
### Step 4

![Intial View](Images/Screenshot%20(6).png)


## How It Works

The program uses the concept of BFS to find the shortest path between two points on the grid. It represents the grid as a matrix and creates an adjacency matrix to determine the connections between grid points.

The `BFS` class implements the BFS algorithm. It has methods to calculate the adjacency matrix and calculate the shortest path using BFS.

The `Body` class sets up the graphical user interface using the turtle module. It handles user interactions, such as clicking on the grid to set start/end points or draw hurdles. It also triggers the BFS algorithm to find the shortest path and displays it on the grid.

## Note

Please ensure that the required dependencies are installed before running the program.
