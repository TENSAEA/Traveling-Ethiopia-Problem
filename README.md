# Traveling Ethiopia

## Overview

The "Traveling Ethiopia" project is a Python-based solution that utilizes graph theory to find optimal paths between cities in Ethiopia. The project implements various pathfinding algorithms, including Breadth-First Search (BFS) and Depth-First Search (DFS), to navigate through a network of cities and roads.

## Project Structure

The project consists of the following key components:

1. **Path Finder Functions**:

   - `uninformed_path_finder`: A function that selects the appropriate pathfinding strategy (BFS or DFS) based on user input.
   - `bfs_path_finder`: Implements the BFS algorithm to find the shortest path between two cities.
   - `dfs_path_finder`: Implements the DFS algorithm to explore paths between cities.

2. **Traverse All Cities**:

   - `traverse_all_cities`: A function that allows traversal of all cities using either BFS or DFS.
   - `bfs_traverse_all`: Uses BFS to visit all cities.
   - `dfs_traverse_all`: Uses DFS to visit all cities.

3. **Visualization**:

   - `visualize_graph`: A function that visualizes the cities and roads as a graph, highlighting the path taken.

4. **Advanced Challenges**:
   - Handling dynamic road conditions and finding k-shortest paths using Dijkstra's algorithm.

## Example Usage

The notebook includes example usage of the implemented functions, demonstrating how to find paths between cities and visualize the results.

## Requirements

- Python 3.x
- NetworkX
- Matplotlib

## Installation

To install the required packages, run:

```bash
pip install networkx matplotlib
```

## Done by: Tensae Aschalew
