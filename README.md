# Term Project: Julia Neural Network Implementation and Exploration

Rather than focusing on the machine learning application, this project will focus more on the linear algebra application. Using Julia, we will focus more on the computational analysis rather than the standard benchmarks for an ML model.

This is taking advantage of the fact that neural nets are just matrix optimization problems.

- Implementing forward and back propagation manually using matrix calculus through Julia
- Studying convergence behavior of gradient descent under different learning rates
- Analyzing conditioning and spectral properties of weight matrices
- Implementing convolutional layers as structured linear operators
  - Toeplitz
  - sparse matrix viewpoint
- Exploring recurrent neural networks as dynamical systems
  - examining stability via eigenvalue
  - spectral radius

The emphasis would be on computational cost, numerical stability, convergence behavior, sparse/dense matrix structure, and performance scaling, rather than achieving high predictive accuracy on a dataset
