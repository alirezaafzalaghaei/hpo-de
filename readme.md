# Hyperparameter Optimization of Orthogonal Functions in the Numerical Solution of Differential Equations

This repository contains the implementation and data related to the paper "Hyperparameter Optimization of Orthogonal Functions in the Numerical Solution of Differential Equations".

## Overview

The implementation of the proposed algorithms is done in Maple and Python programming languages. Specifically:

- **Maple**: Implementation of the CLS-SVR algorithm for solving differential equations using fractional rational Jacobi functions.
- **Python**: Development of grid search, random search, Bayesian optimization, and genetic algorithm for hyperparameter optimization.

The communication between these languages is facilitated via file exchange.

## Repository Structure

- `simple-example/`: Contains the bare-bone implementation of the proposed algorithms.
- `problem-plots/`: Contains source code and data used for generating problem-related plots.
- `comparison-plots/`: Contains source code and data used for generating comparison plots.

## Getting Started

To replicate the results or run the algorithms, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/alirezaafzalaghaei/hpo-de.git
   cd hpo-de
   ```

2. Set up the environment:
Ensure Maple and Python are installed on your system.
```bash
pip install -r requirements.txt
```

3. Run the examples
Navigate to the simple-example folder and follow the instructions in the README file there.

## Contact

For any questions or issues, please open an issue in this repository or contact the authors directly.

## Citation
If this code contributes to your work, please acknowledge it by citing our paper:
```
@article{aghaei2024hyperparameter,
author = {Afzal Aghaei, Alireza and Parand, Kourosh},
title = {Hyperparameter optimization of orthogonal functions in the numerical solution of differential equations},
journal = {Mathematical Methods in the Applied Sciences},
volume = {n/a},
number = {n/a},
pages = {1-24},
year = {2024},
doi = {https://doi.org/10.1002/mma.10346},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/mma.10346},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/mma.10346},
}
```
