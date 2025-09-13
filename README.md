# Multi-Class Neural Network From Scratch (NumPy)

This project implements a **fully connected neural network** for **multi-class classification** from scratch using only **Python + NumPy**, trained on the MNIST dataset.

## Features
- Forward propagation (`tanh` hidden layers, `softmax` output).
- Backpropagation (manual gradient calculation).
- Cross-entropy loss.
- Vectorized implementation (fast training with NumPy).
- Mini-batch gradient descent.
- Achieved ~78% accuracy on MNIST after 20 epochs.

## Data
MNIST dataset (28x28 grayscale digits) from `fetch_openml("mnist_784")`.
- Flattened into 784 features.
- Normalized to [0, 1].
- Example batch shape: `(20, 784)`.
