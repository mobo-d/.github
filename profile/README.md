# Multiobjective Bayesian Optimization based on Decomposition 
Decomposition is a basic strategy for solving multiobjective optimization problems (MOPs), as it enables the simplification of MOPs into more manageable sub-problems [[1](https://ieeexplore.ieee.org/abstract/document/4358754)].  This strategy not only makes the problem-solving process more efficient, but also provides a flexible way to balance between diversity and convergence. This page includes the representative MultiObjective Bayesian Optimization (MOBO) papers that utilize decomposition techniques.

## Random Scalarization
Applie the standard single-objective acquisition function after random scalarization.
* **2006, TEVC. Joshua Knowles. "ParEGO: a Hybrid Algorithm with on-line Landscape Approximation for Expensive Multiobjective Optimization Problems". [[PDF](https://ieeexplore.ieee.org/abstract/document/1583627)]**
* **2020, UAI. Biswajit Paria, Kirthevasan Kandasamy, Barnabás Póczos. "A Flexible Framework for Multi-Objective Bayesian Optimization using Random Scalarizations". [[PDF](https://proceedings.mlr.press/v115/paria20a.html)]**
* **2020, ICML. Richard Zhang, Daniel Golovin. "Random Hypervolume Scalarizations for Provable Mmulti-objective Black Box Optimization". [[PDF](https://proceedings.mlr.press/v119/zhang20i.html)]**

## Decomposition & Cooperation
Following the [MOEA/D](https://ieeexplore.ieee.org/abstract/document/4358754) framework, decompose a MOP in question into a number of sub-problems via a set of reference vectors and solve these sub-problems in a collaborative manner. It is based on the assumption that the optimal solutions of two subproblems should be similar when their reference vectors are close.
* **2010, TEVC. MOEA/D-EGO. Qingfu Zhang, Wudong Liu, Edward Tsang, and Botond Virginas. "Expensive Multiobjective Optimization by MOEA/D with Gaussian Process Model". [[PDF](https://ieeexplore.ieee.org/abstract/document/5353656)] [[code](https://github.com/mobo-d/MOEAD-EGO)]**
* **2022, NeurIPS. PSL-MOBO. Xi Lin, Zhiyuan Yang, Xiaoyuan Zhang, and Qingfu Zhang. "Pareto Set Learning for Expensive Multi-Objective Optimization". [[PDF](https://papers.nips.cc/paper_files/paper/2022/hash/7a583691ccfcf8945ab714b677ccbf0b-Abstract-Conference.html)] [[Supplementary](https://papers.nips.cc/paper_files/paper/2022/file/7a583691ccfcf8945ab714b677ccbf0b-Supplemental-Conference.pdf)] [[code](https://github.com/Xi-L/PSL-MOBO)]**
* **2024, TEVC. DirHV-EGO. Liang Zhao and Qingfu Zhang. "Hypervolume-Guided Decomposition for Parallel Expensive Multiobjective Optimization". [[PDF](https://ieeexplore.ieee.org/document/10093980)] [[Supplementary](https://ieeexplore.ieee.org/document/10093980/media#media)] [[code](https://github.com/mobo-d/DirHV-EGO)]**
  

