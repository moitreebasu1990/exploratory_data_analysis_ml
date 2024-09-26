# Spaceship Titanic: Passenger Transportation Prediction

## Project Overview
The goal of this project is to teach exploratory data analysis techniques using machine learning approaches. It consists of data preprocessing, exploratory data analysis (EDA) steps, and the deployment of a neural network for binary classification.


## Table of Contents
1. [Installation](#installation)
2. [Project Structure](#project-structure)
3. [Usage](#usage)
4. [Data Processing](#data-processing)
5. [Model Architecture](#model-architecture)
6. [Training](#training)
7. [Evaluation](#evaluation)
8. [Kaggle Competition](#kaggle-competition)

## Installation
To run this project, you need to have Python installed along with the following libraries:
- numpy
- pandas
- matplotlib
- scikit-learn
- torch (PyTorch)
- kaggle

You can install these dependencies using pip:

```
pip install numpy pandas matplotlib scikit-learn torch kaggle
```

## Project Structure
The project consists of several main components:
1. Data download and extraction
2. Data exploration and preprocessing
3. Neural network model definition
4. Model training
5. Model evaluation
6. Test set prediction

## Usage
To use this project:
1. Ensure you have a Kaggle account and API credentials set up.
2. Run the script to download and process the data.
3. Train the neural network model.
4. Evaluate the model's performance.
5. Use the trained model to make predictions on the test set.

## Data Processing
The data processing steps include:
- Removing unnecessary columns
- Discretizing the Age column
- Removing outliers
- Normalizing numerical columns
- Handling null values
- Encoding categorical variables
- One-hot encoding for selected features

## Model Architecture
The neural network model (`NNBinaryClassifier`) is a feedforward network with the following structure:
- Input layer
- Four hidden layers with ReLU activation, batch normalization, and dropout
- Output layer with sigmoid activation for binary classification

## Training
The model is trained using:
- Binary Cross-Entropy Loss
- Adam optimizer
- 500 epochs
- Batch size of 16

Training progress is monitored and logged every 100 epochs.

## Evaluation
The model's performance is evaluated using:
- Accuracy score
- Classification report (precision, recall, F1-score)
- Confusion matrix

## Kaggle Competition
This project is part of the Spaceship Titanic competition on Kaggle.
---

Note: Make sure to comply with Kaggle's competition rules and guidelines, and don't copy/use this code for submissions.