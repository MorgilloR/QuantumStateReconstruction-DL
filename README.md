# Quantum State Reconstruction in a Noisy Environment via Deep Learning

This repository contains the code implementation of the paper titled "Quantum State Reconstruction in a Noisy Environment via Deep Learning" ([arXiv:2309.11949](https://arxiv.org/abs/2309.11949)) by Angela Rosy Morgillo [@MorgilloR](https://github.com/MorgilloR) and Stefano Mangini [@stfnmangini](https://github.com/stfnmangini), developed under the supervision of Prof. Chiara Macchiavello and Prof. Marco Piastra. 

The proposed method utilizes a neural network-based approach for quantum state reconstruction.

[![arXiv](https://img.shields.io/badge/arXiv-2404.15266-b31b1b.svg)](https://arxiv.org/abs/2309.11949)

## Repository Organization

The repository is organized as follows:

- `one_qubit.ipynb`: Notebook for pure single-qubit state reconstruction.
- `two_qubit.ipynb`: Notebook for pure two-qubit state reconstruction.
- `three_qubit.ipynb`: Notebook for pure three-qubit state reconstruction.
- `mixed_states.ipynb`: Notebook for mixed single-qubit state reconstruction.
- `multi_qubit_channel.ipynb`: Notebook for two-qubit state reconstruction when a multi-qubit channel is considered (here, correlated amplitude damping for two-qubit states).
- `minimum_fidelity_1q.ipynb`: Notebook exploring the influence of dataset cardinality in single-qubit state reconstruction.
- `minimum_fidelity_2q.ipynb`: Notebook exploring the influence of dataset cardinality in two-qubit state reconstruction.
- `classification_problems.ipynb`: Notebook for classifying different single-qubit quantum channels using neural network-based approaches.
- `plots.ipynb`: Notebook containing plots from the pre-print.
