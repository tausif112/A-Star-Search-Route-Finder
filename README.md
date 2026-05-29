<div align="center">

# ⭐ A* Search Route Finder

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Artificial Intelligence](https://img.shields.io/badge/AI-Artificial%20Intelligence-orange)
![Pathfinding](https://img.shields.io/badge/Pathfinding-AStar-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

### AI-Powered Route Planning using the A* Search Algorithm

Efficient pathfinding and route optimization through heuristic search techniques and graph-based navigation.

<img src="images/designed_map.png" width="700">

</div>

---

# 📌 Project Overview

The **A* Search Route Finder** is an Artificial Intelligence project that demonstrates how the **A* Search Algorithm** can be used to determine the most efficient route between locations.

This system uses a custom-designed address map where locations are represented as nodes and roads are represented as weighted edges. By combining actual travel cost and heuristic estimates, the algorithm efficiently finds the shortest path from a selected location to the **University of Asia Pacific (UAP)**.

The project provides a practical implementation of one of the most widely used search algorithms in Artificial Intelligence, Robotics, GPS Navigation, and Route Optimization Systems.

---

# 🎯 Objectives

The primary objectives of this project are:

* Understand heuristic search algorithms
* Implement the A* Search Algorithm
* Design a custom address map
* Demonstrate graph-based pathfinding
* Visualize route optimization concepts
* Apply Artificial Intelligence techniques to real-world navigation problems

---

# 🚀 Skills Demonstrated

* Artificial Intelligence
* A* Search Algorithm
* Heuristic-Based Search
* Route Optimization
* Graph Theory
* Pathfinding Techniques
* Data Structures
* Python Programming
* Algorithm Design
* Problem Solving

---

# 🛠️ Technologies Used

| Technology           | Purpose                          |
| -------------------- | -------------------------------- |
| Python               | Core Programming Language        |
| A* Search Algorithm  | Pathfinding & Route Optimization |
| Graph Data Structure | Map Representation               |
| Draw.io              | Diagram Design                   |
| Custom Address Map   | Route Simulation                 |

---

# 📂 Project Structure

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
└── diagrams/
    └── a_star_tree_diagram.drawio
```

---

# 🗺️ Designed Address Map

The custom address map used in this project represents real-world route planning concepts through interconnected locations and weighted paths.

![Designed Map](images/designed_map.png)

---

# 🌳 A* Search Tree Diagram

The search process can be visualized through the A* Search Tree Diagram.

📄 **Diagram File:**
[View A* Search Diagram](diagrams/a_star_tree_diagram.drawio)

---

# 🧠 Understanding A* Search

The A* Search Algorithm evaluates nodes using:

```text
f(n) = g(n) + h(n)
```

Where:

* **g(n)** = Actual cost from the start node
* **h(n)** = Estimated cost to the goal node (heuristic)
* **f(n)** = Total estimated path cost

The algorithm always expands the node with the lowest **f(n)** value, allowing it to efficiently find the optimal route while minimizing unnecessary exploration.

---

# ⚙️ How the Algorithm Works

1. Start from the selected source location.
2. Calculate:

   * Actual path cost (g)
   * Heuristic estimate (h)
   * Total cost (f)
3. Expand the node with the smallest f-value.
4. Repeat the process until the destination (UAP) is reached.
5. Reconstruct the optimal route.

This approach guarantees an optimal solution when an admissible heuristic is used.

---

# ✨ Features

✅ Custom-designed address map

✅ Graph-based route representation

✅ Heuristic-guided pathfinding

✅ Optimal route generation

✅ A* Search implementation

✅ Search tree visualization

✅ Educational Artificial Intelligence demonstration

✅ Lightweight and efficient Python implementation

---

# 🎥 Demonstration

The project demonstrates how A* Search efficiently explores the search space and identifies the shortest route from a selected starting location to UAP.

The generated route represents the optimal path based on edge costs and heuristic estimates.

---

# 📊 Applications of A* Search

A* Search is widely used in:

* GPS Navigation Systems
* Route Planning Software
* Robotics Navigation
* Video Game Pathfinding
* Logistics Optimization
* Autonomous Vehicles
* Geographic Information Systems (GIS)

---

# 📖 Learning Outcomes

Through this project, the following concepts were practiced:

* Artificial Intelligence Search Techniques
* Graph-Based Problem Solving
* Heuristic Functions
* Route Optimization
* Data Structures
* Search Space Exploration
* Python Programming
* Algorithm Analysis

---

# 🔍 Why A* Search?

A* Search is considered one of the most effective pathfinding algorithms because it combines:

* Optimality
* Completeness
* Efficiency

Unlike uninformed search techniques, A* uses domain knowledge through heuristic functions, significantly reducing the number of nodes explored.

This makes it one of the most important algorithms in Artificial Intelligence and modern navigation systems.

---

# 👨‍💻 Author

<div align="center">

### Md. Tausif Uddin

Bachelor of Science in Computer Science & Engineering (CSE)
University of Asia Pacific (UAP)

GitHub: https://github.com/tausif112

</div>

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Acknowledgement

This project was developed as part of the Artificial Intelligence and Expert Systems coursework to demonstrate the practical implementation of the A* Search Algorithm for route planning and pathfinding applications.
