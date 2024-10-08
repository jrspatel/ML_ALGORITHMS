# ML Algorithms from Scratch

### Implementation of Linear Regression, Logistic Regression, and Naive Bayes from Scratch

This repository contains Python implementations of three fundamental machine learning algorithms from scratch without using any external machine learning libraries such as `scikit-learn` or `TensorFlow`. The focus is on understanding the underlying math and coding the algorithms manually.

---

## Table of Contents

- [Overview](#overview)
- [Implemented Algorithms](#implemented-algorithms)
- [Installation](#installation)
- [Usage](#usage)


---

## Overview

In this project, we have implemented the following machine learning algorithms:

- **Linear Regression**: A supervised learning algorithm used to predict continuous values based on input features.
- **Logistic Regression**: A supervised learning algorithm used for binary classification tasks.
- **Naive Bayes**: A probabilistic classification algorithm based on Bayes' Theorem with an assumption of independence between predictors.

Each algorithm is built from scratch to understand the working mechanism, without using machine learning libraries.

---

## Implemented Algorithms

### 1. **Linear Regression**
Linear regression is used to predict the relationship between a dependent variable and one or more independent variables. We have implemented:
- Gradient Descent optimization
- Mean Squared Error loss function


### 2. **Logistic Regression**
Logistic Regression is used for binary classification tasks by applying a sigmoid function to model probabilities. The implementation includes:
- Sigmoid function for prediction
- Binary Cross-Entropy loss function
- Gradient Descent optimization

### 3. **Naive Bayes**
Naive Bayes classifier applies Bayes' Theorem for classification, assuming that the features are conditionally independent given the class. The implementation includes:
- Gaussian Naive Bayes for continuous features
- Probability estimation using Bayes' Theorem

---

## Requirements

- Python 3.7+
- `numpy`: For numerical computations
- `pandas`: (Optional) For dataset manipulation
- `matplotlib`: (Optional) For plotting results

---

## Installation

1. Clone this repository:
    ```bash
    https://github.com/jrspatel/ML_ALGORITHMS.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ML_ALGORITHMS
    ```


---

## Usage

Each algorithm is implemented in a separate Python file. You can run the algorithms using a sample dataset by executing the scripts as shown below:


```bash
python linear_regression.py
python logistic_regression.py
python naive_bayes.py
```


