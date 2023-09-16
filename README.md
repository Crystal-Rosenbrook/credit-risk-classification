# credit-risk-classification

## Credit Risk Classification with Logistic Regression, Analysis and Report

### Homework Files: credit_risk_classification_and_report.ipynb and lending_data.csv

### Overview
This repository contains Python code that uses logistic regression to predict credit risk. The model uses historical loan data to predict whether a loan is at high-risk or low-risk of defaulting. We evaluate two logistic regression models: one based on the original data and another based on oversampled data to balance the classes.

## Prerequisites
- Python 3.x
  
- NumPy
  
- pandas
  
- scikit-learn
  
- imbalanced-learn

## How to Run the Code
Clone the repository to your local machine.
Navigate to the directory where the code resides.
Run the code using a Python environment.

## Imported Required Libraries
```python
import numpy as np

import pandas as pd

from pathlib import Path

from sklearn.metrics import balanced_accuracy_score, confusion_matrix, classification_report

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

from imblearn.over_sampling import RandomOverSampler
```

## References
Referenced course files, Stack Overflow, Slack, scikit-learn.org, imbalanced-learn.org, docs.python.org, geeksforgeeks.org and ChatGPT to complete this homework

## Dataset
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
