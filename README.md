# MachineLearning2DIsingModel

Pedagogical notebooks and supporting material for learning the thermal phase transition of the 2D square-lattice Ising model using supervised deep learning.

Reproduces one of the figures from [J. Carrasquilla and R. G. Melko, Machine Learning Phases of Matter, Nat. Phys. 13, 431 (2017)](https://www.nature.com/articles/nphys4035); [arXiv version](https://arxiv.org/abs/1605.01735).

The core idea is to generate (or load) spin configurations across temperature, train a neural network to classify phases (ordered vs disordered), and use its performance to identify the critical region.

## Repository Format

- `src/` : Jupyter notebooks (data generation, training, evaluation, plots)
- `data/` : saved configurations, labels 
- `include/` : helper files

