---
layout: page
title: Project
permalink: /project/
---
### Algorithm Configuration for a MIP Solver
Perform a small to medium-scale computational study of algorithm configuration (see Lecture 4) for a MIP or MIP-based solver. A "MIP solver" here refers to tools such as SCIP, Gurobi, CPLEX, Xpress, i.e., tools for solving Mixed Integer Linear Programs (deterministic, single-objective). A "MIP-based solver" may be a software tool (that is available in open-source or free for academic use) for tackling integer optimization problems beyond the linear/single-objective/deterministic case, for example the many projects from [Coin-OR](https://www.coin-or.org/projects/) or [Google's OR-Tools](https://developers.google.com/optimization), a versatile optimization package with APIs in Python and other languages, as well as specialized heuristics for some classes of combinatorial optimization problems (routing, packing, scheduling, etc.).

Compare some of the following approaches on one or more datasets (of optimization instances), controlling a subset of parameters which you think are interesting (e.g., branching parameters, preprocessing parameters, etc.):
- Default parameter setting;
- A solver's own parameter tuning tool (if any);
- Random sampling of parameter configuration;
- An advanced algorithm configuration tool, e.g., [ParamILS](http://www.cs.ubc.ca/labs/beta/Projects/ParamILS/), [SMAC](https://automl.github.io/SMAC3/master/).

Use best practices for analyzing experimental results (see Lecture 3).	

### ML-guided Stochastic Local Search for a Combinatorial Problem
The books on [Stochastic Local Search](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_askewsholts_vlebooks_9780080498249) and [Integer Programming](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_askewsholts_vlebooks_9781119606550) discuss a variety of local search heuristics for combinatorial optimization problems. Oftentimes, these heuristics involve a significant amount of manual engineering in their steps.

Select (1) a combinatorial optimization problem, (2) a stochastic local search algorithm, and (3) one or more relevant datasets (publicly available or that you generate based on the literature), and apply a Machine Learning approach that can tailor the algorithm (2) to a dataset (3) from a problem (1). Use best practices for analyzing experimental results (see Lecture 3).

### Apply RL+GNN to a new Graph Optimization problem	

https://github.com/Hanjun-Dai/graph_comb_opt	https://github.com/wouterkool/attention-learn-to-route

### Implement a Combinatorial Optimization environment in RLlib	https://docs.ray.io/en/latest/rllib.html	

### Conceptual and experimental analysis/extension of the OR-Gym paper and code repository	https://arxiv.org/abs/2008.06319	

### A 2021 in-depth analysis of this 1999 classic [Smith, Kate A. “Neural networks for combinatorial optimization: a review of more than a decade of research.” INFORMS Journal on Computing 11.1 (1999): 15-34.] [link]	https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_proquest_journals_200517105 	

### Apply ML (of any flavor) to a problem you are interested in		