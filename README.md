# Shortest_path

This program finds the shortest path to other buildings from the Computer Science building using both the Bellman-Ford and Dijkstra algorithms.

## Description

The program constructs a graph representing a campus map where buildings are nodes and paths between buildings are edges. It then applies the Bellman-Ford and Dijkstra algorithms to find the shortest paths from the Computer Science building to all other buildings.

## How to Use

1. Ensure you have Python installed on your system.
2. Clone or download the program files to your local machine.
3. Open a terminal or command prompt.
4. Navigate to the directory containing the program files.
5. Run the program
6. The program will output the shortest paths from the Computer Science building to all other buildings.

## Input Data

The input data representing the graph is provided within the program code itself. Each line in the `data_lines` list represents an edge between two buildings along with the distance between them. You can change the data according to your use 

## Dependencies

This program does not have any external dependencies.

## Additional Notes

- The `Building` and `Graph` classes are defined to represent the campus map and its buildings.
- The `bellman_ford` and `Dijkstra` functions implement the Bellman-Ford and Dijkstra algorithms, respectively.
- Results of both algorithms are printed to the console, showing the shortest paths from the Computer Science building to other buildings.



