# Category Determination Project

This repository contains the code for a category determination project using two different models: Linear Support Vector Classifier (Linear SVC) and Neural Networks (NN).

## Table of Contents

- [Project Structure](#project-structure)
  - [Neural Network Model (`nn.py`)](#neural-network-model-nnpy)
    - [Description](#description)
    - [Dependencies](#dependencies)
    - [Installation](#installation)
  - [Linear Support Vector Classifier Model (`linearsvc.py`)](#linear-support-vector-classifier-model-linearsvcpy)
    - [Description](#description-1)
    - [Dependencies](#dependencies-1)
    - [Installation](#installation-1)
- [Instructions for Running the Code](#instructions-for-running-the-code)

## Project Structure

### Neural Network Model (`nn.py`)

#### Description
The `nn.py` script contains the code for the Neural Network (NN) model used for category determination.

#### Dependencies
- `pandas`
- `numpy`
- `matplotlib`
- `csv`
- `keras`
- `sklearn.metrics`
- `tensorflow.keras.models`
- `tensorflow`
- `hazm` (for Persian text processing)

### Linear Support Vector Classifier Model (`linearsvc.py`)

#### Description
The `linearsvc.py` script contains the code for the Linear Support Vector Classifier (Linear SVC) model used for category determination.

#### Dependencies
- `pandas`
- `numpy`
- `sklearn.pipeline`
- `sklearn.feature_extraction.text`
- `sklearn.preprocessing`
- `sklearn.svm` (LinearSVC)
- `hazm` (for Persian text processing)

#### Installation
You can install the required dependencies using the following command:

```
pip install pandas numpy matplotlib keras scikit-learn tensorflow hazm

```
## Instructions for Running the Code

To run these scripts and reproduce the results:

1. Make sure you have all the required dependencies installed as listed in the respective script descriptions.
2. Download the dataset files (not included in this repository) and place them in the same directory as the scripts.
3. Run the `nn.py` and `linearsvc.py` scripts to train the models and make predictions.

Feel free to customize the code and experiment with different parameters to improve the performance of the models.

**Note**: Make sure to properly credit and reference the source of the pre-trained word embeddings (fastText) in your project.
