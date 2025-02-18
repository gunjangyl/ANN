# ANN

# Simple ANN Implementation for Binary Classification

This project demonstrates a basic implementation of an Artificial Neural Network (ANN) from scratch using NumPy in Python.  It focuses on a single-layer perceptron for binary classification tasks.

## Project Overview

The code implements a neural network that learns to classify input data into one of two categories (0 or 1). It uses the sigmoid activation function and a gradient descent approach for training.

## Files

- `ANN implementation.ipynb`: The Jupyter Notebook containing the Python code.

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[gunjangyl]/[ANN].git  
   cd [ANN]
Set up a Virtual Environment 



Code Description
The notebook contains the following key sections:

Import NumPy: Imports the necessary NumPy library.<br>
Sigmoid Function: Defines the sigmoid activation function and its derivative. Note: The derivative function provided in the original code might be incorrect. If the input x to the derivative function is the output of the sigmoid function, then x*(1-x) is correct. However, if the input x is the input to the sigmoid function, the correct derivative is sigmoid(x)*(1-sigmoid(x)). Please double-check and correct this if necessary.<br>
Training Data: Sets up the training input and output data using NumPy arrays.<br>
Weight Initialization: Initializes the weights of the neural network (currently to zero).<br>
Training Loop: Implements the training process, including forward propagation, error calculation, and weight updates.<br>
Output: Prints the network's output on the training data after training.<br>
Requirements:<br>
Create a requirements.txt file in your repository and list the project dependencies:<br>

numpy
jupyter


Author- Gunjan Goyal
