# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=1800&pause=1000&color=6962B6&vCenter=true&width=431&height=30&lines=AI%3A+EMOC%3A+Evolutionary+MultiObjective+Computing%F0%9F%92%BB)](https://git.io/typing-svg)


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

<img src="Multi-objective optimization/example_images/output_ZDT1.png" alt="Pareto Front Example" width="500"/>

#### ZDT3

<img src="Multi-objective optimization/example_images/output_zdt3.png" alt="Pareto Front Example" width="500"/>

#### MW7

<img src="Multi-objective optimization/example_images/output_mw7.png" alt="Pareto Front Example" width="500"/>

#### MW14

<img src="Multi-objective optimization/example_images/output_mw14.png" alt="Pareto Front Example" width="500"/>

#### TSP-MultiObjective

<img src="Multi-objective optimization/example_images/output_tsp-mo.png" alt="Pareto Front Example" width="500"/>
