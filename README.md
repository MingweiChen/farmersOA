# farmersOA

## File Directory
 - Kiosk Coords.csv is the file which contains the original geographical data
 - distance.txt. is the file which contains the distance matrix which is acquired with Google Map API
 - path.py is the source code

## Overview
It requires finding the shortest loop path cover all nodes in the graph.
This is an NP problem, specifically called TSP problem.
I did a research about the possible algorithm:
 - Naive: Use DFS to traverse all nodes and get the shortest path, the time complexity is O(n!), it is too slow.
 - Dynamic Programming: It requires 2^n space complexity. It is impossible to be run on current machines.
 - Branch and Bound Method: It is based on naive version and requires some pruning. My code is based on the algorithm.
Also, there are some heuristic algorithm, e.g. genetic algorithm and simulated annealing. They are targeted at local optimum rather than the global optimum.

## Demo
 - make sure you have installed python 2.7 and pip

 - install google maps python API
```
sudo pip install googlemaps
```
 - run the script 
```
python path.py
```
