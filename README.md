
# Mind vs. Machine

## A Machine Learning Classification Framework for AI Dependency in Generative Writing Tasks

This project investigates dependency-related patterns in human–AI collaborative writing using behavioural interaction metadata and survey responses from the CoAuthors dataset.

### Project Overview

The project applies a CRISP-DM-guided data science workflow involving data cleaning, integration, normalisation, feature engineering, dependency index construction, and supervised machine learning.

### Dataset

- Source: CoAuthors human–AI collaborative writing dataset
- Final observations: 828 writing sessions
- Engineered features: Six behavioural and psychological constructs
- Classification categories: Low, Moderate, and High

### Machine Learning Models

- Random Forest Classifier — 83.13% reported holdout accuracy
- Decision Tree Classifier — 80.72% reported holdout accuracy
- Random Forest five-fold cross-validation — 84.42% mean accuracy

### Technologies

Python, Jupyter Notebook, pandas, NumPy, scikit-learn, Matplotlib, and Seaborn.

### Important Limitation

The dependency categories were constructed from the same six features used to train the classifiers. Consequently, the reported performance represents classification of operationally defined categories rather than independently validated psychological AI dependency detection.

### Project Output

A notebook-based behavioural analytics dashboard presents selected model results, feature importance, and cross-validation performance.

### Academic Context

Final-year Data Science capstone project.
