# Deep_Learn_Project


# AlphabetSoupCharity Optimized Model

This Jupyter notebook builds and evaluates an optimized deep neural network model to predict successful charity donations based on the AlphabetSoup charity dataset.

## Improvements Over Base Model

The key optimizations done compared to the base AlphabetSoupCharity model notebook are:

- Deeper neural network architecture with 5 hidden layers instead of 3
- Different activation function - LeakyReLU instead of ReLU
- Additional regularization via dropout layers
- RMSprop optimizer instead of default Adam optimizer
- Various other training hyperparameter tuning

## Contents

The notebook contains the following key sections:

**Data Import and Preprocessing** 

- Imports libraries 
- Loads charity dataset
- Handles categorical data
- Splits dataset into train/test

**Data Scaling and Encoding**

- Scales features for effective training
- Encodes categorical variables into numeric

**Model Definition and Training**

- Defines deep neural network architecture
- Compiles and trains model for 100 epochs
- Tunes hyperparameters for improved performance 

**Model Evaluation** 

- Evaluates model loss and accuracy
- Exports model to HDF5 file

## Setup and Results

The optimized model achieves ~73% test accuracy compared to 72% for the base model. Further tuning of model architecture and training process could improve accuracy more.

The notebook requires Python 3 and common data science libraries like Pandas, TensorFlow and Scikit-Learn.

The trained deep learning model is exported to `AlphabetSoupCharity_optimized.h5` file for later use.
