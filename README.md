# Determining Catagory

This repository contains the code for a category determination project using two different models: Linear Support Vector Classifier (Linear SVC) and Neural Networks (NN).

## Table of Contents

1. [Introduction](#introduction)
2. [Neural Network Model (NN.py)](#neural-network-model-nnpy)
3. [Linear Support Vector Classifier (linearsvc.py)](#linear-support-vector-classifier-linearsvcpy)
4. [Dataset and Features](#dataset-and-features)
5. [Installation](#installation)

## Introduction

Provide a brief introduction to your project, including its purpose and any important context.

## Neural Network Model (NN.py)

NN.py contains the code for implementing a Neural Network model for text classification. It uses libraries such as Keras and TensorFlow to build and train the model. Below are the key steps and components of the code:

- Importing necessary libraries.
- Loading and preprocessing the dataset.
- Creating word embeddings using FastText.
- Building the Neural Network model architecture.
- Training the model and evaluating its performance.
- Making predictions on test data.

## Linear Support Vector Classifier (linearsvc.py)

The linearsvc.py file contains code for implementing a Linear Support Vector Classifier for text classification. Here are the main steps and components of the code:

- Importing libraries, including scikit-learn and Hazm.
- Loading and preprocessing the dataset.
- Creating a pipeline for text classification.
- Training the Linear Support Vector Classifier.
- Making predictions on both training and test data.

## Dataset and Features

The dataset used in this project is the SummerCamp 1400 CafeBazaar dataset. It consists of the following features:

- "app_id": Application ID (not used in this project).
- "description_fa": Persian language descriptions of applications.
- "label": Labels indicating the category of each application.

The dataset was preprocessed, and word embeddings were created using pre-trained FastText vectors for the Persian language.

## Installation

To use this project, you need to install the following dependencies:

- https://pandas.pydata.org/: `pip install pandas`
- https://numpy.org/: `pip install numpy`
- https://matplotlib.org/: `pip install matplotlib`
- https://keras.io/: `pip install keras`
- https://scikit-learn.org/: `pip install scikit-learn`
- https://github.com/sobhe/hazm: `pip install hazm`
- https://pypi.org/project/fasttext/: `pip install fasttext`

Make sure to run these commands in your Python environment to install the necessary libraries.
