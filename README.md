# PATH-FINDER


This Python script demonstrates graph visualization and pathfinding using NetworkX library. It creates a graph based on nodes and edges, finds the shortest path between nodes considering weights, and visualizes the graph with paths overlaid on a background image.

## Requirements
- Python 3.x
- NetworkX
- Matplotlib
- Requests

## Usage

1. Clone the repository or download the Python script.
2. Install the required libraries using `pip install networkx matplotlib requests`.
3. Run the script in your preferred Python environment.

### Functionality

- The script allows two types of inputs:
    - Source-Destination Input: Input two locations to find the shortest path between them.
    - Source-Weight Input: Input a start location and a maximum weight to find paths within that weight limit from the start location.

- The graph is created using a set of nodes and edges, each having specific weights.
- The script utilizes Dijkstra's algorithm for pathfinding.
- It visualizes the graph and highlights the shortest path(s) on a given background image.

### Usage Example
