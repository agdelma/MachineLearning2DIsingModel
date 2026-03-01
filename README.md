# MachineLearning2DIsingModel

Pedagogical notebooks and supporting material for learning the thermal phase transition of the 2D square-lattice Ising model using supervised deep learning.

Reproduces one of the figures from [J. Carrasquilla and R. G. Melko, Machine Learning Phases of Matter, Nat. Phys. 13, 431 (2017)](https://www.nature.com/articles/nphys4035); [arXiv version](https://arxiv.org/abs/1605.01735).

The core idea is to generate (or load) spin configurations across temperature, train a neural network to classify phases (ordered vs disordered), and use its performance to identify the critical region. For the 2D Ising model at zero field, the exact critical temperature is
\[
k_B T_c / J = \frac{2}{\ln(1+\sqrt{2})} \approx 2.269185\ldots
\]

## Repository Format

- `src/` : Jupyter notebooks (data generation, training, evaluation, plots)
- `data/` : saved configurations, labels 
- `include/` : helper files

## Quickstart

Clone the repo:
```
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

