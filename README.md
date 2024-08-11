# Shortest Path Calculator using Dijkstra's Algorithm

This Python script calculates the shortest path between geographical locations using Dijkstra's algorithm. The script takes into account the latitude and longitude of each location to compute the distance and direction between nodes.

## How to Run the Script

1. **Ensure Python is Installed:** The script requires Python 3.x.

2. **Run the Script:**
   ```sh
   python shortestPath.py


# Shortest Path Calculator

## Requirements

- **Python 3.x**
- **math library:** Standard with Python

## Features

- **Haversine Formula:** Calculates the distance between two points on the Earth's surface given their latitude and longitude.
- **Direction Calculation:** Determines the cardinal direction (N, NE, E, SE, S, SW, W, NW) based on the latitude and longitude differences between two points.
- **Dijkstra's Algorithm:** Implements Dijkstra's algorithm to find the shortest path between nodes in a graph, taking into account the distances and directions.

## Example Use Case

This script can be used for GPS navigation and mapping applications where determining the shortest path between two geographical points is essential. It calculates the actual physical distance between locations and provides the optimal route, considering both the distance and direction.

## Contributing

Contributions are welcome! If you'd like to contribute, please submit a Pull Request with your changes..


### Explanation:
- **Header Sections:** Clearly labeled sections for title, how to run, requirements, features, example use case, contributing, and license.
- **Code Blocks:** Proper usage of code blocks for both commands and script outputs.
- **Instructions:** Step-by-step guide on how to run the script and what input/output to expect.
- **Example Use Case:** Added a section explaining a potential use case for the script.

## Output:
# Shortest Path Calculation

## Usage Example

```shell
C:\Users\anike\AppData\Local\Programs\Python\Python39\python.exe "D:\Python Program\com\company\Cosmica GPS\shortestPath.py"
Enter the number of edges in the graph: 3
Enter the starting node: A
Enter the ending node: C
Enter the latitude of A: 18.5305
Enter the latitude of A: 73.8472
Enter the latitude of C: 18.5974
Enter the latitude of C: 73.7187
Enter the starting node: B
Enter the ending node: C
Enter the latitude of B: 18.5074
Enter the latitude of B: 73.8077
Enter the latitude of C: 18.5974
Enter the latitude of C: 73.7187
Enter the starting node: C
Enter the ending node: D
Enter the latitude of C: 18.5974
Enter the latitude of C: 73.7187
Enter the latitude of D: 18.5987
Enter the latitude of D: 73.7706
Enter the start point: A
Enter the end point: D
Path: A (N) ----> C (NW) ----> D (NE)
Shortest distance covered: 20.92 km

Vertex         Distance from Source
C              0.00 km
C              15.45 km
D              20.92 km
Process finished with exit code 0
