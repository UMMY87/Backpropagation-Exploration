# Backpropagation Exploration

This repository contains a Python code snippet that explores the fundamentals of backpropagation, a crucial concept in neural networks. Below is a breakdown of the code:

## Overview

The code snippet begins by importing necessary libraries and setting up the environment for plotting. It then defines a neural network using a provided configuration.

## Symbolic Differentiation

The code proceeds to perform symbolic differentiation to compute gradients for the parameters of the network. It calculates derivatives with respect to weights and biases, which are essential for updating the network parameters during the training process. The calculations involve applying the chain rule of calculus to compute gradients efficiently.

## Application of Derivatives

Furthermore, the code demonstrates the application of these derivatives in a specific example. It involves the calculation of the loss function and its gradient with respect to the network parameters. Additionally, it investigates the behavior of these gradients by introducing small perturbations and observing the resulting changes in the loss function.

## Comparison with Numerical Approximations

Finally, the code computes and prints various derivatives such as $\( \frac{\partial J}{\partial w} \)$, $\( \frac{\partial J}{\partial b} \)$, and $\( \frac{\partial J}{\partial x} \)$. It then compares them with numerical approximations to validate the correctness of the symbolic differentiation process.

## Conclusion

In summary, this code provides a foundational understanding of how backpropagation works by symbolically computing derivatives and using them to update the parameters of a neural network to minimize a given loss function. It serves as a fundamental building block for training neural networks in machine learning.
