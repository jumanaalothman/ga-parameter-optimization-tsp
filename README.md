# Meta-Optimization of Genetic Algorithm Parameters for Solving the Traveling Salesman Problem

## Overview

This repository contains the first phase of my graduation project, which focuses on meta-optimization of Genetic Algorithm parameters for solving the Traveling Salesman Problem (TSP).

The Traveling Salesman Problem is a well-known NP-hard optimization problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the starting point. Genetic Algorithms are commonly used to solve complex optimization problems such as TSP, but their performance is highly affected by parameter settings such as population size, crossover rate, and mutation rate.

This project studies how Parameter Meta-Optimization (PMO), machine learning, and adaptive strategies can improve the performance of Genetic Algorithms by reducing manual parameter tuning and supporting better parameter selection.

## Project Status

- Phase 1: Completed
- Phase 2: In progress

## Problem Background

Genetic Algorithms can provide good solutions for TSP, but their performance depends heavily on choosing suitable parameter values. Poor parameter settings may lead to slow convergence, premature convergence, or low-quality solutions.

Traditional methods such as manual tuning or using default parameter values may not generalize well across different TSP instances. Therefore, this project investigates automated parameter optimization methods to improve GA performance.

## Project Goal

The main goal of this project is to enhance the performance of Genetic Algorithms for solving TSP by combining offline and online parameter meta-optimization approaches.

The proposed direction includes:

- Offline parameter prediction using meta-learning
- Online parameter adjustment using an Adaptive Genetic Algorithm
- Neural Network-based prediction of GA parameters
- Evaluation using standard TSP benchmark instances

## Key Concepts

- Traveling Salesman Problem (TSP)
- Genetic Algorithms (GA)
- Parameter Meta-Optimization (PMO)
- Hyperparameter Optimization (HPO)
- Meta-Learning
- Neural Networks
- Adaptive Genetic Algorithm
- Population Size
- Crossover Rate
- Mutation Rate

## Phase 1 Content

Phase 1 focused on the research foundation and project planning. It includes:

- Problem statement and motivation
- Background on TSP, optimization algorithms, Genetic Algorithms, and Neural Networks
- Literature review of offline, online, and hybrid PMO methods
- Proposed hybrid framework
- Methodology design
- Experimental design and planned evaluation metrics

## Proposed Methodology

The project proposes a hybrid framework that combines:

1. An offline Neural Network model to predict suitable initial GA parameter values based on TSP instance features.
2. An online Adaptive Genetic Algorithm to dynamically adjust parameters during execution.

This hybrid approach aims to improve solution quality, convergence speed, and computational efficiency.

## Technologies and Tools

- Python
- Google Colab
- Machine Learning
- Neural Networks
- Genetic Algorithms
- Optimization
- Data Analysis

## Datasets

The project plans to use TSP benchmark instances, including TSPLIB instances, to evaluate the proposed approach.

## What I Learned

- How Genetic Algorithms are applied to NP-hard optimization problems
- How GA parameters affect solution quality and convergence
- How Parameter Meta-Optimization can automate parameter tuning
- How offline and online optimization approaches differ
- How machine learning can support optimization tasks
- How to structure and document a research-based computer science project

## Notes

This repository currently includes Phase 1 of the graduation project. Phase 2, including implementation, experiments, and final evaluation, is currently in progress and will be added after completion.
