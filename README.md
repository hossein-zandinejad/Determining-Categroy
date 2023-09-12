# Project Name

Description of your project goes here.

## Table of Contents

1. [Introduction](#introduction)
2. [Neural Network Model (NN.py)](#neural-network-model-nnpy)
3. [Linear Support Vector Classifier (linearsvc.py)](#linear-support-vector-classifier-linearsvcpy)
4. [Dataset and Features](#dataset-and-features)
5. [Usage](#usage)

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

## Usage

Provide instructions on how to use your code. Include any prerequisites, installation steps, and examples of running the code.
