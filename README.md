# Student Placement Prediction

A Machine Learning project that predicts student placement outcomes using CGPA and IQ as input features. The project uses Logistic Regression for binary classification and demonstrates the complete basic Machine Learning workflow from data preprocessing to prediction and evaluation.

## Project Overview

The objective of this project is to build a classification model that predicts whether a student will be placed based on their CGPA and IQ.

The target variable is:

- `0` - Not Placed
- `1` - Placed

The project was created to understand the fundamentals of Machine Learning, including training data, test data, feature scaling, model training, prediction, and model evaluation.

## Dataset

The dataset contains information about students and their placement status.

### Features

| Feature | Description |
|---------|-------------|
| CGPA | Student's CGPA |
| IQ | Student's IQ score |

### Target

| Value | Meaning |
|-------|---------|
| 0 | Not Placed |
| 1 | Placed |

## Machine Learning Workflow

```text
Dataset
   |
   v
Feature and Target Selection
   |
   v
Train-Test Split
   |
   v
Feature Scaling
   |
   v
Logistic Regression
   |
   v
Model Training
   |
   v
Prediction
   |
   v
Model Evaluation
   |
   v
Decision Boundary Visualization