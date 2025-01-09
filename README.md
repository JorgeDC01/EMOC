# BIOCOMP-Project

Evolutionary Algorithms Project
This project focuses on developing and implementing evolutionary algorithms to solve optimization problems. The work is divided into two main parts:

1. Single-Objective Optimization
- Himmelblau’s Function: A continuous optimization problem with four global optima in the search space 
[−5,+5]. The implementation includes:
  - Custom evolutionary algorithms adapted for real-number encodings.
  - Hybridization with a local search method using gradient descent to refine solutions.
- Traveling Salesman Problem (TSP): A combinatorial optimization problem with 100 cities. The solution involves:
  - Evolutionary algorithms designed for permutation-based encodings.
  - Custom operators to minimize the total route distance.



2. Multi-Objective Optimization
Extended the previously developed algorithms to tackle multi-objective problems, focusing on achieving Pareto-optimal fronts. Problems solved include:
  - Standard benchmark functions like ZDT1, ZDT3, MW7, and MW14.
  - Multi-objective TSP, optimizing for both distance and time metrics.
- Compared custom algorithms against NSGA-II using metrics such as hypervolume, spread, and spacing.
- Visualized Pareto fronts to evaluate performance.

All implementations were carried out in Python, leveraging libraries such as NumPy and Pymoo for certain multi-objective benchmarks and visualizations.

An example of problem's Pareto fronts are the following ones:

#### ZDT1



#### ZDT3



#### MW7



#### MW14



#### TSP-MultiObjective

