# Campus Navigation System (Using BFS & DFS)

This project simulates a **Campus Navigation System** using **graph traversal algorithms** - **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**.

---

## How to Run

1. Clone the repository:  

2. Open the Jupyter notebook:  
   `Campus_Navigation_System.ipynb`
3. Run each cell to:  
   - Build the graph  
   - Apply BFS and DFS  
   - View the visualizations


##  Example

```python
start = "Library"
end = "Playground"
path = campus.bfs_shortest_path(start, end)

Output:
Shortest path from Library to Playground is:
Library ➝ Canteen ➝ Playgroun
