# deep-learning-challenge

This repository contains a deep learning model created using TensorFlow/Keras to predict the success of funding applications for Alphabet Soup Charity. The model aims to assist Alphabet Soup in making data-driven decisions on which organizations to fund, maximizing the impact of their donations.

## Files Included
- AlphabetSoupCharity.ipynb: Jupyter Notebook containing the initial deep learning model creation and evaluation.

- AlphabetSoupCharity_Optimization.ipynb: Jupyter Notebook containing the optimized deep learning model with improved performance.
- AlphabetSoupCharity.h5: HDF5 file containing the trained model.
- report.md: Report containing analysis and findings of the deep learning model.
- README.md: This file, providing an overview of the repository and instructions.

## Overview
### The analysis involves:

1. Data Preprocessing:

- Identifying target and feature variables.
- Removing non-beneficial columns.
- Binning rare occurrences in APPLICATION_TYPE and CLASSIFICATION.
- Converting categorical variables into dummy variables.

2. Model Creation:

- Initial Model Architecture:
	- Three-layer neural network with ReLU activation functions.
- Optimized Model Architecture:
	- Increased number of neurons and hidden layers for improved performance.

3. Model Evaluation:

- Initial Model Performance:
	- Loss: 0.5593, Accuracy: 72.52%
- Optimized Model Performance:
	- Loss: 0.5801, Accuracy: 73.11%

## Usage Instructions
1. Clone the repository to your local machine:


git clone https://github.com/Neil7777/deep-learning-challenge

2. Open and run the Jupyter Notebooks:

    - AlphabetSoupCharity.ipynb: Initial model creation and evaluation.
    - AlphabetSoupCharity_Optimization.ipynb: Optimized model creation and evaluation.

 3. Ensure you have the required libraries installed:

    - pandas
    - numpy
    - scikit-learn
    - tensorflow

4. Train, optimize, and evaluate the deep learning model for Alphabet Soup Charity Fund predictions.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- tensorflow