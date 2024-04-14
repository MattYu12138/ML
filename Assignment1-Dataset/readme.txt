# Neural Network Implementation Using Multilayer Perceptron (MLP)

This repository contains the implementation of a neural network using the Multilayer Perceptron (MLP) architecture with various customization options like dropout, batch normalization, and different activation functions.

## Overview

The code is structured to perform the following tasks:

1. Load and preprocess data from `.npy` files.
2. Define and initialize an MLP model with configurable layers, activation functions, dropout rates, and batch normalization.
3. Train the MLP using mini-batch gradient descent with momentum or Adam optimization.
4. Evaluate the trained model on both training and testing datasets.
5. Calculate and print basic statistics of the training data.

## File Descriptions

- `train_data.npy`: Training dataset features.
- `train_label.npy`: Training dataset labels.
- `test_data.npy`: Testing dataset features.
- `test_label.npy`: Testing dataset labels.

## Model Configuration

The MLP is built to be highly configurable. Here are the elements you can adjust:

- Number of layers and their sizes
- Type of activation functions for each layer
- Dropout rates for each layer to control overfitting
- Whether to apply batch normalization
- L2 regularization strength (weight decay)
- Learning rate and momentum for the optimizer

## Running the Code

To run the code, make sure you have the following prerequisites installed:

- Python 3.x
- NumPy

Load your datasets into the same directory as the script, and run the Python file. The network will begin training and will output the training and testing accuracies after completion.

## Expected Outputs

- Train and test accuracies printed to console
- Loss values printed per epoch during training
- The final evaluated accuracy on the test dataset

## Hyperparameters and Optimization

You can tweak the hyperparameters and optimization settings as per your requirements. This includes adjusting the learning rate, the momentum factor for updates, the number of epochs, and the batch size during training.


