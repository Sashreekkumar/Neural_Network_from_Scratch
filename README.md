# Spiral Dataset Neural Network

This project implements a neural network from scratch using only NumPy and Pandas, designed to classify the challenging spiral dataset. The network achieves **93% accuracy** by learning complex non-linear patterns inherent in the dataset.

## Features

- Fully custom implementation of neural network components
- Dense layers with ReLU activation
- Softmax output layer for multi-class classification
- Categorical Cross-Entropy loss from scratch
- Adam optimizer for efficient training
- Manual forward and backward propagation
- Achieves ~93% accuracy on the spiral dataset

## Dataset

The project uses the spiral dataset provided by the `nnfs` library, where each sample has two features representing coordinates, and the target corresponds to one of three classes forming a spiral pattern.

## Future Work

Future improvements may include:

- Experimenting with deeper architectures or more neurons per layer
- Adding regularization techniques to reduce overfitting
- Implementing learning rate schedules for faster convergence
- Visualizing decision boundaries to better understand model predictions

