# Multiobjective Bayesian Optimization based on Decomposition 
Decomposition is a basic strategy for solving multiobjective optimization problems (MOPs), enabling the simplification of MOPs into more manageable sub-problems. This page includes the representative MultiObjective Bayesian Optimization (MOBO) papers that utilize decomposition techniques.

## Random scalarization
Applie the standard single-objective acquisition function after random scalarization.
* **2006, TEVC. [ParEGO: a hybrid algorithm with on-line landscape approximation for expensive multiobjective optimization problems](https://ieeexplore.ieee.org/abstract/document/1583627).**
* **2020, UAI. [A Flexible Framework for Multi-Objective Bayesian Optimization using Random Scalarizations](https://proceedings.mlr.press/v115/paria20a.html).**
* **2020, ICML. [Random hypervolume scalarizations for provable multi-objective black box optimization](https://proceedings.mlr.press/v119/zhang20i.html).**

## Decomposition & Cooperation
Following the [MOEA/D](https://ieeexplore.ieee.org/abstract/document/4358754) framework, decompose a MOP in question into a number of scalarized sub-problems via a set of reference vectors and solve these sub-problems in a collaborative manner. It is based on the assumption that the optimal solutions of two subproblems should be similar when their reference vectors are close.
### Using a finite number of reference vectors
* **2010, TEVC. [Expensive Multiobjective Optimization by MOEA/D with Gaussian Process Model](https://ieeexplore.ieee.org/abstract/document/5353656).**
* **2017, CEC. [An efficient batch expensive multi-objective evolutionary algorithm based on Decomposition](https://ieeexplore.ieee.org/abstract/document/7969460).**
* **2024, TEVC.[Hypervolume-Guided Decomposition for Parallel Expensive Multiobjective Optimization](https://ieeexplore.ieee.org/document/10093980).**
  
### Pareto Set Learning (infinite number of reference vectors)
* **2022, NeurIPS. [Pareto Set Learning for Expensive Multi-Objective Optimization](https://arxiv.org/abs/2210.08495).**
