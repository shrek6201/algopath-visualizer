# Algorithm Visualization Application

This is a visualizing application made to help coders visualize how an algorithm maps and traverses through a given grid.

## Features

- Provides an empty grid structure by default with the starting node and the target node already set.
- Offers three maze types for the algorithms to traverse and map:
  - No Maze (default)
  - Binary Tree
  - Recursive Division
- Provides four algorithms for visualization:
  - A-Star
  - Breadth First Search (default)
  - Depth First Search
  - Dijkstra
- Allows users to choose the speed at which the algorithm works through a given maze:
  - Fast (default)
  - Medium
  - Slow

## How It Works

1. By default, the application has 'No Maze' selected as its Maze type, 'Breadth First Search' as the algorithm, and 'Fast' as the speed.
2. Users can select any of the three mazes by clicking on the drop-down menu. They can then select any one of the four algorithms and any one of the three speed types.
3. After selecting the required parameters, users can click the play button, which starts the selected algorithm.
4. When the selected algorithm is working, users cannot select any more mazes, algorithms, or speed types. They must wait until the algorithm has finished working.
5. After the algorithm has finished working, the play button turns into a reset button, which, when clicked, resets the mapping of the previous algorithm and clears the maze.

## Customization

Potential users can clone this repository and edit the application as they see fit. Users can also add new maze types and algorithms.
