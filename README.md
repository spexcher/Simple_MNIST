# Simple MNIST Classifier in PyTorch

This repository contains the implementation of a basic neural network classifier using PyTorch, trained on the famous MNIST dataset of handwritten digits. The goal of this project is to demonstrate the fundamental concepts of neural networks, including forward and backward propagation, loss functions, and optimization, with a specific focus on the mathematical foundations behind the process.

## Project Overview

The **MNIST (Modified National Institute of Standards and Technology)** dataset is a classic benchmark for image classification algorithms. This dataset contains 70,000 grayscale images of handwritten digits, each 28x28 pixels in size. The task is to classify each image into one of ten categories (digits 0 through 9).

The neural network model in this project is a simple single-layer neural network (also known as multinomial logistic regression or softmax classifier). The model is trained using **stochastic gradient descent (SGD)** to minimize the **cross-entropy loss** function.

## Features

- **Mathematical Explanation**: Detailed mathematical formulation for forward and backward propagation, including softmax, cross-entropy loss, and gradient descent.
- **PyTorch Implementation**: A simple neural network implemented using PyTorch, including the training loop and model evaluation.
- **Numerical Example**: An example demonstrating how softmax and loss calculations are carried out for a single sample.
- **Model Evaluation**: Code to evaluate the model's performance on the test set and print the accuracy.

## Installation
```bash
pip install torch torchvision numpy matplotlib
```
### Prerequisites

Before running the code, make sure you have Python 3 and the required libraries installed. You can use `pip` to install them:

```bash
pip install torch torchvision numpy matplotlib
```

#Cloning the Repository
To clone this repository, run the following command:

```bash
git clone https://github.com/spexcher/Simple_MNIST.git
cd Simple_MNIST
```
#Running the Code
To train the model and evaluate the accuracy, simply run the ipynb in Jupyter Notebook
