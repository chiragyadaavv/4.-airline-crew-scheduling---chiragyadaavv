# Airline Crew Scheduling – NP-Hard Problem Solving

## Overview
This project provides a backtracking-based solver for the airline crew scheduling problem. Given a set of flights and available crew members, the goal is to generate valid crew schedules that satisfy non-overlapping flight assignments, minimum rest periods, and optionally, cost optimization.

- **Domain**: Resource Allocation in Aviation
- **Strategy**: Backtracking (Constraint Satisfaction)
- **Time Complexity**: O(k × 2ⁿ) where n = number of flights, k = crew
  
## Problem Statement
Assign a set of flights (with start and end times) to crew members subject to:
- No overlapping assignments for any crew member
- At least 1 hour rest between flights for any crew member
- Optionally, minimize total cost or maximize fairness

## How to Run
1. Clone/download this repository and set up a Python 3.10+ environment.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Open `crew_scheduling_notebook.ipynb` and follow through each section.

## Directory Structure
- `crew_scheduling_notebook.ipynb` - Main code, visualizations, and explanations (run notebooks here).
- `requirements.txt` - Dependencies.
- `images/` *(optional)* - Gantt charts or output screenshots.
- `.gitignore` *(optional)* - To exclude files/folders like `.ipynb_checkpoints` and `venv`.

## References
- [Airline Crew Scheduling Problem – Wikipedia](https://en.wikipedia.org/wiki/Crew_scheduling)
- [Memory Profiler for Python](https://pypi.org/project/memory-profiler/)
- [Matplotlib Documentation](https://matplotlib.org/stable/gallery/lines_bars_and_markers/broken_barh.html)