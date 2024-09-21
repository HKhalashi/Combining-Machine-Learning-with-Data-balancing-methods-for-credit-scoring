# Combining Machine Learning with Data-balancing Methods for Credit Scoring

This repository contains the code, datasets, and report related to the project "Combining Machine Learning with Data-balancing Methods for Credit Scoring." This project was conducted in the fall of 2022 as a university project.

## Project Overview

The project aims to explore and improve credit scoring using machine learning models combined with data-balancing techniques. Credit scoring is vital for financial institutions to assess the risk of default on loans, especially when the dataset is imbalanced (where good credit cases greatly outnumber bad ones). 

### Objective
The primary goal of this study is to determine the best combination of machine learning models, feature selection methods, and data-balancing techniques for handling imbalanced datasets in credit scoring.

## Methods

The following machine learning models were applied in the experiments:
- **Random Forest (RF)**
- **Neural Network (NN)**
- **Gradient Boosted Tree (XGB)**
- **Logistic Regression (LR)**

### Feature Selection Techniques:
- **L1-based feature selection with support vector machine (SVM)**
- **Random Forest Recursive Feature Elimination (RF-RFE)**

### Data Balancing Techniques:
- **Random Oversampling**
- **SMOTE (Synthetic Minority Oversampling Technique)**
- **SMOTETomek**
- **SMOTEOSS**

## Datasets

Two datasets were used in this project:

1. **[UCI Credit Card Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)**
   - **Size**: 30,000 samples, 24 features
   - **Imbalance Ratio**: 3.5
   - The dataset contains information on demographic factors, credit data, and payment history of credit card clients from April 2005 to September 2005.
   
2. **[Default Dataset](https://rdrr.io/cran/ISLR/man/Default.html)**
   - **Size**: 10,000 samples, 4 features
   - **Imbalance Ratio**: 29.02
   - This is a simulated dataset used for predicting customer default on credit card debt.

## Experiments

Each dataset underwent the following steps:
1. Data preprocessing and feature selection.
2. Application of different machine learning models combined with various data-balancing techniques.
3. Evaluation using performance metrics including Accuracy, Sensitivity, Specificity, and AUC-ROC.

## Results

The key findings from the experiments are:
- **UCI Credit Card Dataset**: The best performance was achieved using a **Neural Network (NN)** with **Random Oversampling** and **L1 Feature Selection**, achieving an AUC of 0.749.
- **Default Dataset**: A **Neural Network (NN)** with **SMOTETomek** and **RF-RFE** provided strong sensitivity and balanced overall performance.

## Conclusion

The study concludes that for imbalanced datasets in credit scoring, **Random Forest** or **Neural Network** classifiers combined with data-balancing techniques such as **Random Oversampling**, **SMOTETomek**, and **RF-RFE** are the most effective approaches. Logistic Regression showed significantly worse performance as the dataset imbalance increased.
