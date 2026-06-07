# Lab 1 Part A: OOP Search Algorithms for Drone Pathfinding

**Student:** Rafiatou Malam Ali

**Student ID:** 30782027

**Course:** Introduction to Artificial Intelligence

**Date:** 07/06/2026

---

## Overview

This lab implements uninformed search algorithms for an autonomous drone navigating a grid environment with obstacles. The drone must find a path from a start location to a goal location while avoiding obstacles such as dense forests, water bodies, dangerous pits, and restricted zones.

## Algorithms Implemented

| Algorithm | Description |
|-----------|-------------|
| **BFS** | Breadth-First Search - uses FIFO queue, finds shortest path |
| **DFS** | Depth-First Search - uses LIFO stack, memory efficient |
| **DLS** | Depth-Limited Search - DFS with depth limit, uses path-cycle checking |
| **IDS** | Iterative Deepening Search - repeatedly calls DLS with increasing limits |

## Files in This Repository

| File | Description |
|------|-------------|
| `Rafiatou_Malam_ali_Lab_1A.ipynb` | Main Jupyter notebook with complete implementation |
| `AI_USE_DECLARATION.md` | AI use declaration form as required by course |
| `README.md` | This file |

## Maps Tested

1. **Sample Map** - 10×10 grid provided in lab instructions
2. **Custom Map 1** - 15×15 grid with obstacle patterns
3. **Custom Map 2** - 20×20 maze-like structure with corridors

## How to Run

1. Open `Rafiatou_Malam_ali_Lab_1A.ipynb` in Jupyter Notebook or Google Colab
2. Run all cells from top to bottom
3. The notebook will display:
   - Comparison tables for all algorithms
   - Visualized solution paths
   - Performance metrics (nodes expanded, frontier size, solution depth)

## Results Summary

- **BFS** finds the shortest path but uses more memory
- **DFS** is memory efficient but may not find the shortest path
- **DLS** prevents infinite depth exploration with a limit
- **IDS** combines benefits of BFS and DFS with repeated searching

## Requirements

- Python 3.7+
- Jupyter Notebook or Google Colab
- Required libraries: numpy, pandas, matplotlib

## GitHub Repository

[https://github.com/rafiatoumalamali-cell/Rafiatou_Malam_ali_AI_lab1.git](https://github.com/rafiatoumalamali-cell/Rafiatou_Malam_ali_AI_lab1.git)

## Declaration

I declare that this work is my own. AI tools were used as declared in `AI_USE_DECLARATION.md` and do not exceed 25% of the total work.

---

**Signature:** RMA

**Date:** 07/06/2026
