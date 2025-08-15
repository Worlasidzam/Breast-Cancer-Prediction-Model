# Breast-Cancer-Prediction-Model
A Logistic Regression Model trained to predict breast cancer.
## Project Overview
This project focuses on predicting breast cancer (malignant or benign) using a Logistic Regression model. The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset from Kaggle, which contains various features computed from digitized images of fine needle aspirates (FNA) of breast masses.
## Key Features:
Data preprocessing including handling missing values and label encoding,
Exploratory data analysis to understand the dataset,
Feature scaling using StandardScaler,
Model training with Logistic Regression,
Performance evaluation using accuracy score, confusion matrix, and classification report.
## Data Set:
The dataset(from Kaggle) contains 569 samples with 32 features including:
Radius mean,
Texture mean,
Perimeter mean,
Area mean,
Smoothness mean,
Compactness mean,
And other computed features.
Target variables: Diagnosis(Malignant=1, Benign=0).
## Results:
The Logistic Regression model achieved:
**Accuracy**: 98.6%,
**Precision**: 98% for benign, 100% for malignant,
**Recall**: 100% for benign, 96% for malignant,
**F1-score**: 99% for benign, 98% for malignant.
## Requirements:
Python 3.x,
Pandas,
NumPy,
Scikit-learn,
Seaborn,
Matplotlib.
## How to run:
**Install the required packages**,
**Download the dataset from Kaggle (or use the provided data.csv)**,
**Run the Jupyter notebook breast_cancer_prediction.ipynb**.

## Possible Further Improvements:
Experiment with other classification algorithms,
Perform feature selection to improve model performance,
Develop a web application for real-time predictions,

## Acknowledgment
**Dataset from UCI Machine Learning Repository (available on Kaggle)**,
**Scikit-learn documentation for model implementation guidance**.
