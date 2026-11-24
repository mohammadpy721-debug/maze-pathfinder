# 🧩 Maze Pathfinder

A small, dependency-free maze visualizer. It generates a random maze with the recursive backtracker algorithm, then solves it with **BFS** or **A\*** and animates the search.

## Features
- Random perfect-maze generation (recursive backtracker)
- BFS and A\* pathfinding, with live animation
- Stats per run: path length, cells explored, time in ms
- Adjustable maze size, light and dark themes

## Run it
Open `index.html` in any browser. No build step or install needed.

## How it works
- **BFS** explores cells in layers and always finds the shortest path.
- **A\*** uses the Manhattan distance to the goal as a heuristic, so it usually explores fewer cells while still finding the shortest path.
