# A* Search Based Address Map to UAP

Implementation of the A* Search Algorithm to find the optimal route from a selected location to the University of Asia Pacific (UAP) using a custom-designed address map.

---

## Project Overview

This project demonstrates how the A* Search Algorithm works in real-world pathfinding and route optimization problems.

The map is represented as a graph where:
- Nodes represent locations
- Edges represent paths/roads
- Heuristic values guide the search toward the destination

The algorithm efficiently determines the shortest and most optimal route to UAP.

---

## Objectives

- Understand heuristic search algorithms
- Implement the A* Search Algorithm
- Build a custom address map
- Visualize pathfinding concepts
- Apply graph-based route optimization

---

## Technologies Used

- Python
- A* Search Algorithm
- Graph Data Structure
- Draw.io
- Custom Map Design

---

## Project Structure

```text
A-Star-Search-Route-Finder/
│
├── README.md
├── main.py
├── requirements.txt
│
├── images/
│   └── designed_map.png
│
├── diagrams/
│   └── a_star_tree_diagram.drawio
│
└── report/
    └── CSE404_LabReport2.pdf
```

---

## Designed Address Map

![Designed Map](images/designed_map.png)

---

## A* Search Tree Diagram

[View Diagram](diagrams/a_star_tree_diagram.drawio)

---

## How A* Search Works

The algorithm uses:

```text
f(n) = g(n) + h(n)
```

Where:
- `g(n)` = actual cost from start node
- `h(n)` = heuristic estimated cost to goal
- `f(n)` = total estimated cost

The node with the lowest `f(n)` value is selected at each step.

---

## Features

- Custom address map
- Heuristic pathfinding
- Optimal route generation
- Graph visualization
- Educational AI lab implementation

---

## Report

The detailed project report is available inside the `report` folder.

---

## Author

**Md. Tausif Uddin**  
Department of Computer Science and Engineering  
University of Asia Pacific
