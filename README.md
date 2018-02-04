# farmersOA

## File Directory
Kiosk Coords.csv is the file which contains the original geographical data
distance.txt. is the file which contains the distance matrix whcih is accquired with Google Map API
path.py is the source code

## Overview
It requires to find a shortest loop path cover all nodes in gragh.
This is an NP problem, specifically called TSP problem.
I did research about the possible algorithm:
 - Naive: Use DFS to traverse all nodes and get the shortest path, the time complexity is $$O(n!)$$, it is too slow.
 - Dynamic Programming: It requires $$2^n$$ space complxity. It is impossible to be run on current machines.
 - Branch and Bound Method: It is based on naive version and requires some pruning.

## Demo
sudo pip install googlemaps


