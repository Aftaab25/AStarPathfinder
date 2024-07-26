# A* Pathfinder

This repository contains an implementation of the A* (A-Star) pathfinding algorithm in Python. The A* algorithm is a popular search algorithm used in various applications such as AI, robotics, and game development to find the shortest path between two points.

## Features

- **A\* Algorithm**: Efficiently finds the shortest path between the start and goal nodes.
- **Visualization**: Provides a visual representation of the grid, obstacles, start, and goal nodes, and the path found by the algorithm.
- **Interactive UI**: Allows users to interact with the grid, set start and goal nodes, and add obstacles.

## Getting Started

### Prerequisites

- Python 3.x
- Pygame

### Installation

Clone the repository:
   ```bash
   git clone https://github.com/Aftaab25/AStarPathfinder.git
   cd AStarPathfinder
   ```

### Running the App

Run the A* pathfinding script using the following command:
```bash
python3 main.py
```

This will start the application, and you can interact with the grid to visualize the A* pathfinding algorithm.

## Before using A* Algorithm
Select the start and end point by clicking any of the box in the grid.
    _(First click corresponds to the start point and the Second click corresponds to the end point)_

Then click anywhere in the grid to draw obstacles in the path that the algorithm has to avoid.

![Before Image](screenshots/before_algo.png)

Press `Space` to start the visualization of the algorithm and see the result _(the shortest path possible)_ drawn by the algorithm.

## Result Path by the A* Algorithm
![Result Image](screenshots/result_path.png)

Press `Enter` to clear the grid and draw new maps to play with.


## Code Overview

### `main.py`

- **Imports**: Necessary libraries including Pygame and heapq.
- **Node Class**: Represents a single node in the grid with attributes like position, cost, heuristic, and parent.
- **A* Algorithm**: Implements the A* search algorithm to find the shortest path.
- **Visualization**: Uses Pygame to visualize the grid, obstacles, start and goal nodes, and the path found by the algorithm.
- **Event Handling**: Handles user input for setting start and goal nodes, adding obstacles, and resetting the grid.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
