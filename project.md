---
layout: page
title: Project
permalink: /project/
---
## Potential Ideas

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
As discussed in the surveys by Mazyavkina et al. and Cappart et al. (see Syllabus), the combination of Reinforcement Learning (RL) and Graph Neural Networks (GNN) has been used successfully to guide algorithms for some combinatorial algorithms.

This project builds on this research direction by repurposing or augmenting existing open-source repositories that combine RL+GNN to a new optimization problem.

Existing repositories (along with the corresponding papers) that may serve as a good starting point include:
- `https://github.com/Hanjun-Dai/graph_comb_opt`	
- `https://github.com/wouterkool/attention-learn-to-route`

### Implement a Combinatorial Optimization environment in RLlib
Triggered by successes in using RL for the game of Go, Atari, and other games, the ML/Computer Systems communities have made significant progress in open-sourcing tools that streamline the application of RL to new domains. An example of such a tool is [RLlib](https://docs.ray.io/en/latest/rllib.html).

Because RL can naturally model iterative algorithms from combinatorial optimization (see Mazyavkina et al. survey in Syllabus), and because developing high-performance RL systems and training algorithms is challenging and already quite developed, we would like to leverage existing RL systems, such as RLlib, to apply RL to combinatorial problems.

In this project, you will study RLlib's features and develop [custom environments](https://docs.ray.io/en/latest/rllib-env.html) for combinatorial optimization, assess the pros and cons of such an approach as compared to implementing combinatorial environments from scratch, perform a set of experiments assessing your solution ideally on 2-3 combinatorial problems.  

### Conceptual and experimental analysis/extension of the OR-Gym paper and code repository
Supply Chain Management (SCM) is a central domain for Operations Research. The [OR-Gym paper](https://arxiv.org/abs/2008.06319) introduces an RL framework for SCM-type problems along with an open implementation.

In this project, you will analyze this paper carefully and propose ways of extending OR-Gym to new SCM-type problems. The book [Fundamentals of Supply Chain Theory](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/14bjeso/alma991106884440206196) is a good reference for the SCM-optimization landscape. Other SCM problems that you may be familiar with are also valid choices.

### A 2021 in-depth analysis of [Smith (1999)](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_proquest_journals_200517105)
This survey precedes the "Deep Learning revolution" of the 2010s. This project revisits the 1999 survey with a critical lens, asking questions such as:

- How does the framing of ML+Combinatorial Optimization in 1999 differ from that of the 2020s (e.g., as seen in the survey by Bengio et al., see Syllabus)?
- Which of the ideas surveyed by Smith in 1999 are worth revisiting with new tools from deep learning (e.g., GNNs, deep RL, etc.)?
- Which of Smith's 1999 ideas for promising future directions ended up materializing since?
- ... and more.

You will analyze the methods surveyed by Smith and use literature review tools (e.g., Google Scholar's "cited by" feature) to understand how this field evolved following the survey, mapping out relevant papers that can answer the questions above or others.

### Apply ML (of any flavor) to a problem you are interested in
Some of you have already approached me with concrete project ideas.

## Computing Resources
Please refer to [this guide from CARTE](https://carte.utoronto.ca/education/cloud-resources/) for ways you can get access to free CPU/GPU resources if needed.

## Datasets of Optimization Instances
- [Ecole's random instance generators](https://doc.ecole.ai/py/en/stable/howto/instances.html)
- [Variety of datasets from Antonio Frangioni](http://pages.di.unipi.it/frangio/)
- [Variety of datasets from Leandro Coelho](https://www.leandro-coelho.com/instances/)
- [Brescia Benchmarks (mostly routing problems)](https://or-brescia.unibs.it/instances)
- [Bin Packing Library](http://or.dei.unibo.it/library/bpplib)
- [Orienteering Problem Library](https://unicen.smu.edu.sg/oplib-orienteering-problem-library)
- [Vehicle Routing Problem Repository](http://www.vrp-rep.org/)
- [Project Scheduling Problem Library](http://www.om-db.wi.tum.de/psplib/)
- ["NEW INSTANCES FOR MAXIMUM WEIGHT INDEPENDENT
SET FROM A VEHICLE ROUTING APPLICATION"](https://arxiv.org/abs/2105.12623)
- [Sports scheduling](https://www.sportscheduling.ugent.be/ITC2021/)
