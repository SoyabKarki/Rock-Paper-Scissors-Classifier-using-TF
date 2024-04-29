# Rock Paper Scissors Classifier

This repository contains code for a Rock Paper Scissors classifier implemented using TensorFlow and Keras. The classifier is trained on the Rock Paper Scissors dataset available in TensorFlow Datasets.

## Introduction

The notebook explores different approaches to classify images of rock, paper, and scissors hand gestures.

## Dependencies

- TensorFlow
- TensorFlow Datasets
- Keras Tuner
- NumPy
- Matplotlib

## Data Preparation

The Rock Paper Scissors dataset is loaded from TensorFlow Datasets and preprocessed for training.

## Model Architectures

### First Approach: ANN

A simple Artificial Neural Network (ANN) architecture is tried initially, resulting in overfitting with an accuracy of 60%.

### Second Approach: Simple CNN

To address overfitting, a basic Convolutional Neural Network (CNN) architecture is implemented. However, the simple CNN achieves only 54% accuracy, indicating room for improvement.

### Third Approach: Tuned CNN

To improve performance, hyperparameter tuning is conducted using Keras Tuner. 10 different models with varying hyperparameters are trained, and the best model achieves an accuracy of 77%.

## Hyperparameter Tuning

Keras Tuner is used to search for the best hyperparameters for the CNN model, resulting in significant improvement in accuracy compared to the simple CNN architecture.

## Saving and Loading Models

Demonstration of saving and loading the best performing model for future use is provided, ensuring that the trained model can be reused without retraining.
