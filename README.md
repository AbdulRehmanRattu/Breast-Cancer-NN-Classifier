# Breast Cancer Neural Network Classifier

## Project Overview
This project implements a neural network from scratch using Python and NumPy to classify breast cancer data. The data is sourced from the well-known Breast Cancer Wisconsin (Diagnostic) dataset, which is available in the `sklearn` library.

## Features
- **Data Standardization:** Standardizes the features to have zero mean and unit variance.
- **Neural Network Implementation:** Builds a simple feedforward neural network with two hidden layers.
- **Activation Function:** Uses the sigmoid activation function for non-linearity.
- **Backpropagation:** Implements the backpropagation algorithm to update the network weights and biases.
- **Performance Evaluation:** Evaluates the classifier on the test set to determine its accuracy.

## Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset, which includes measurements from digitized images of a fine needle aspirate (FNA) of a breast mass. It contains features for each cell nucleus, and the objective is to classify them as malignant or benign.

## Neural Network Architecture
- **Input Layer:** Matches the number of features (30 features from the dataset).
- **Hidden Layers:** Two hidden layers, each with 128 neurons.
- **Output Layer:** One neuron, outputting the probability of the input being malignant.

## Requirements
To run this project, you will need Python and the following Python libraries installed:
- NumPy
- scikit-learn

## How to Run
1. Ensure you have Python and the necessary libraries installed.
2. Download the project files to your local machine.
3. Run the script with the following command:
   ```bash
   python ML.ipynb
