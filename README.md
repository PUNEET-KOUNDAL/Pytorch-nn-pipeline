# PyTorch Core Neural Network Pipeline

## Overview

This repository is dedicated to understanding the core pipeline of PyTorch neural networks with minimal dependencies. The primary objective is to learn how PyTorch works internally rather than optimizing for accuracy.

In this project, we implement and train a single neuron from scratch using only essential PyTorch operations, avoiding high-level abstractions like torch.nn modules. This helps in gaining a deeper understanding of the underlying computations.

## Features

Pure PyTorch Implementation: No use of torch.nn.Module, focusing only on tensors and operations.

Manual Weight Initialization: We manually define and update the weights without using pre-built optimizers.

Custom Forward and Loss Functions: Understanding how forward propagation and loss calculations work at a fundamental level.

Minimalistic Training Loop: Direct computation of gradients and weight updates using torch.autograd.

Implementation Details

Neuron: A single neuron with a sigmoid activation function.

Loss Function: Binary Cross-Entropy (BCE) implemented manually.

Gradient Calculation: Using torch.autograd for automatic differentiation.

Dataset: Simple synthetic dataset for demonstration purposes.

## Code Structure

├── main.py          # Core implementation of the single neuron
├── README.md        # Project documentation

Running the Code


## Goals

✅ Understand PyTorch's computational graph and autograd mechanism.✅ Learn how tensors, gradients, and weight updates work at a low level.✅ Gain insights into the PyTorch training pipeline without focusing on accuracy.

Notes

This project is not aimed at achieving high accuracy but rather at learning how PyTorch builds and trains a neural network from scratch.

Contributions and discussions on improving conceptual clarity are welcome!
