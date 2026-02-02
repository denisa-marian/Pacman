# Pacman Artificial Intelligence Project

## Overview
This project focuses on implementing fundamental and advanced Artificial Intelligence algorithms for controlling the Pacman agent in a grid-based environment.  
The Pacman game framework was provided as part of the university coursework, while **all search and decision-making algorithms were implemented by me**.

The project was developed for the **Artificial Intelligence** course and demonstrates classic AI techniques applied to pathfinding, heuristic search, and multi-agent decision making.

---

## Project Scope
The goal was to design intelligent agents capable of navigating the maze efficiently, collecting food, and reacting to adversarial ghost agents under different constraints.

Pacman operates in a discrete 2D grid environment, where each move represents a state transition. The agent must make real-time decisions based on the current game state.

---

## Implemented Algorithms

### Single-Agent Search
Implemented in `search.py` and `searchAgents.py`:
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**
- **Uniform-Cost Search (UCS)**
- **A\*** search with admissible and consistent heuristics

These algorithms allow Pacman to:
- Find valid paths through the maze
- Compute optimal or near-optimal routes
- Collect all food efficiently

---

### Advanced Search Problems
- **Corners Problem** – visiting all four maze corners with state tracking
- **Food Search Problem** – collecting all food using heuristic optimization
- Custom heuristics based on Manhattan distance and maze distance caching

---

### Multi-Agent Search
Implemented in `multiAgents.py`:
- **Reflex Agent** with evaluation functions
- **Minimax Agent**
- **Alpha-Beta Pruning**
- **Expectimax Agent**

These agents model adversarial and stochastic behavior of ghost agents and allow Pacman to anticipate future game states.

---

## Technologies & Concepts
- Python
- Artificial Intelligence fundamentals
- State-space search
- Heuristic design
- Adversarial search
- Multi-agent systems
- Game tree exploration and pruning

---

## What I Implemented
- All search algorithms and heuristics
- State representations and successor functions
- Evaluation functions for intelligent decision making
- Optimization techniques (alpha-beta pruning, heuristic caching)

The game engine, visualization, and environment setup were provided by the course framework.

---

## Academic Context
- **Course:** Artificial Intelligence  
- **Year:** 3rd year, Bachelor's degree  
- **Institution:** Technical University  
- **Purpose:** Educational project for applying AI algorithms in a game-based environment

---

## Conclusion
This project provided hands-on experience with core Artificial Intelligence algorithms and demonstrated how classical AI techniques can be applied to real-time decision-making problems in dynamic and adversarial environments.

<img width="1251" height="838" alt="image" src="https://github.com/user-attachments/assets/eec27abb-63e1-4b71-9b53-3259d1e127db" />

<img width="1245" height="852" alt="Screenshot 2026-02-02 232505" src="https://github.com/user-attachments/assets/208ca98f-0ba9-424c-ad31-ec48b011152a" />

<img width="420" height="194" alt="image" src="https://github.com/user-attachments/assets/11372478-153c-4e86-a15e-626739a14ef4" />

