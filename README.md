# Intelligent Mobile Robot Navigation
MCTA3371 Mini Project

## Description
2D robot navigation using a Hybrid Fuzzy Logic + Genetic Algorithm controller.

## How to Run
1. Install Python 3 IDE (ex: thonny or pycharm)
2. Install scikit-fuzzy
3. Install numpy
4. Install deap
5. Install matplotlib
3. Run: `ciminiproject.py`

## Features
- Fuzzy Logic controller for real-time navigation decisions
- Genetic Algorithm to optimise fuzzy membership parameters
- Two maps: Simple and Maze
- GUI with Evaluation tab showing Fuzzy vs Fuzzy+GA comparison

## Results
| Controller | Map | Success Rate | Avg Steps |
|---|---|---|---|
| Fuzzy Only | Map 1 Simple | 0% | 500 |
| Fuzzy Only | Map 2 Maze | 100% | 229 |
| Fuzzy + GA | Map 1 Simple | 100% | 364 |
| Fuzzy + GA | Map 2 Maze | 100% | 173 |
