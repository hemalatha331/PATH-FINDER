<div align="center">
<b> <h1>PATH-FINDER</h1> </b>
</div>

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
    - Source-Weight Input: Input a start location and a maximum weight(Example-Distance,Time) to find paths within that weight limit from the start location.

- The graph is created using a set of nodes and edges, each having specific weights.
- The script utilizes Dijkstra's algorithm for pathfinding.
- It visualizes the graph and highlights the shortest path(s) on a given background image.

### Usage Example
For better understandibility let consider a example,A company having multiple branches around country and there is for Inspection team to visit branches and inspect need and overall performance profits and loss of each branch.So in a day while visiting branches it would be better to choose a shortest path reach a company branch rather than longest distance path right?So here is the solution for this ,just enter Source location and Destination location and got display the shortest path with available paths.Secondary category also there that is the inspection team want to reach a brach with some weight(Example Distance or Time etc) limit and they want to reach Destination within that limit.Hence for this solution is just enter the source location and then limit then it display shortest path with available paths.  
