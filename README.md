# Causal Inference Research — Sequential Experimental Design

Undergraduate research project at Dartmouth College exploring optimal 
sequential experimental design under budget constraints, with applications 
to causal structure recovery in high-dimensional settings.

## Research Overview

A central challenge in fields like genomics and systems engineering is 
understanding the causal relationships between variables — which inputs, 
when changed, produce meaningful effects on outputs. Learning these 
relationships requires running experiments, but exhaustive testing is 
infeasible when the number of possible interventions is large.

This project investigates how to sequentially select the most informative 
experiments under a budget constraint, using tools from causal inference, 
linear algebra, and optimization. The goal is both empirical (testing 
strategies on simulated data) and theoretical (proving bounds on the 
performance of proposed strategies).

> **Note:** This repository is a work in progress. Code and findings will 
> be updated incrementally as the research develops.

## Repository Structure

- `simulation.ipynb` — synthetic data generator for a sparse linear model 
  with low-rank covariance structure

## Acknowledgements

Advised by Professor Mazaheri, Department of Computer Science, Dartmouth College.
