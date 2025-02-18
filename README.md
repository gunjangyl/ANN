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
   git clone [https://github.com/](https://github.com/)[your_github_username]/[your_repository_name].git  # Replace with your repo URL
   cd [your_repository_name]
Set up a Virtual Environment (Recommended):



python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt # See "Requirements" section below. Create requirements.txt file with necessary libraries.
Open the Jupyter Notebook:



jupyter notebook
Navigate to ANN implementation.ipynb and run the cells in order.

Code Description
The notebook contains the following key sections:

Import NumPy: Imports the necessary NumPy library.
Sigmoid Function: Defines the sigmoid activation function and its derivative. Note: The derivative function provided in the original code might be incorrect. If the input x to the derivative function is the output of the sigmoid function, then x*(1-x) is correct. However, if the input x is the input to the sigmoid function, the correct derivative is sigmoid(x)*(1-sigmoid(x)). Please double-check and correct this if necessary.
Training Data: Sets up the training input and output data using NumPy arrays.
Weight Initialization: Initializes the weights of the neural network (currently to zero; random initialization is generally recommended).
Training Loop: Implements the training process, including forward propagation, error calculation, and weight updates.
Output: Prints the network's output on the training data after training.
Requirements
Create a requirements.txt file in your repository and list the project dependencies:

numpy
jupyter


Author- Gunjan Goyal
