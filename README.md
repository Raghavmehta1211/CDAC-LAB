# AI-Based Malware Detection System

## Overview
This project implements a Machine Learning-based Malware Detection System that classifies software as either **Malware** or **Goodware** using behavioral features extracted from executable files.

The system applies multiple machine learning algorithms to detect malicious software and compare their performance.

## Features
- Data preprocessing and analysis
- Malware and Goodware classification
- Decision Tree Classifier
- Logistic Regression Classifier
- Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Train-Test Split for validation

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

## Dataset
The project uses the **DynamicMalwareMatrix2.csv** dataset.

The dataset contains:
- Behavioral and dynamic analysis features
- Labels indicating:
  - `1` → Goodware
  - `-1` → Malware

## Machine Learning Models

### 1. Decision Tree Classifier
- Trained using Scikit-Learn
- Generates classification predictions
- Evaluated using confusion matrix and accuracy score

### 2. Logistic Regression
- Data standardized using StandardScaler
- Trained with Logistic Regression
- Compared against Decision Tree performance

## Workflow

1. Import required libraries
2. Load malware dataset
3. Separate features and labels
4. Split dataset into training and testing sets
5. Train Decision Tree model
6. Evaluate model performance
7. Apply feature scaling
8. Train Logistic Regression model
9. Compare model results

## Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Project Structure
