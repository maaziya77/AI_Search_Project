# AI_Search_Project
Implementation of BFS, Greedy, and A* search algorithms for optimal route finding in Japan.
# Optimal Route Finding in Japan Using Search Algorithms

## Project Overview
This project explores search algorithms by solving an optimal route-finding problem using real-world data from Japanese cities. The goal is to find the best travel route from **Makurazaki** to **Nemuro** using both uninformed and informed search strategies. The project demonstrates the application of BFS, Greedy Best-First Search, and A* Search algorithms.


## Algorithms Implemented
1. **Breadth-First Search (BFS)** – Uninformed search algorithm exploring all nodes at each level.  
2. **Greedy Best-First Search** – Informed search using **Haversine distance** as a heuristic.  
3. **A* Search** – Informed search using:  
   - Heuristic 1: Haversine Distance  
   - Heuristic 2: Custom admissible heuristic developed through research  

## Methodology
- Cities are represented as nodes in a graph.  
- Each city is connected to its **8 nearest neighbors** based on **Haversine distance**.  
- The total cost is the **distance traveled** from Makurazaki to Nemuro.  
- Algorithms are compared based on **path optimality, execution time, and nodes expanded**.  

## Key Findings
- BFS guarantees the shortest path but may expand many nodes, making it slower.  
- Greedy Best-First is faster but does not always find the optimal path.  
- A* Search balances speed and optimality, especially when using well-designed heuristics.  
- Heuristic design strongly impacts efficiency and path quality.  

## How to Use
1. Open the **AI_Search_Algorithms_Project.ipynb`** notebook in Google Colab.  
2. Ensure **japan_cities.csv** is in the same folder or uploaded in Colab.  
3. Run all cells to replicate the results, visualizations, and performance metrics.  

## References
- SimpleMaps World Cities Database – Japanese cities subset  
- Haversine Distance Formula
- AI and search algorithm lecture materials  
