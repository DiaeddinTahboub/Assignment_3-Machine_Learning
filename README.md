# Assignment 3 - Machine Learning
This repository contains materials for **Assignment 3** of the Machine Learning course. The assignment focuses on analyzing the diabetes dataset and building predictive models.

## Repository Contents

- **Assignment_3.ipynb**: Jupyter Notebook containing the full data analysis and machine learning workflow.
- **diabetes_data.csv**: Dataset used for training and testing the models.
- **assignment_3.pdf**: Assignment brief that outlines the objectives and tasks.
- **Report.pdf**: Final report summarizing the analysis, methodology, and conclusions.
- **README.md**: This file, providing an overview of the project.

## Project Overview

The goal of this assignment is to develop predictive models for diabetes diagnosis using patient health data. The notebook walks through data preprocessing, exploratory data analysis (EDA), model development, and evaluation.

## Dataset

The dataset `diabetes_data.csv` contains various medical and demographic features relevant to diabetes, including:

- Glucose level
- Blood pressure
- Body Mass Index (BMI)
- Age
- And others

Each row represents an individual patient.

## Main Components

### 1. Data Preprocessing

- Handling missing or invalid values
- Encoding categorical variables
- Feature scaling and normalization

### 2. Exploratory Data Analysis (EDA)

- Descriptive statistics and summaries
- Visualizations using Matplotlib and Seaborn
- Correlation heatmaps and distribution plots

### 3. Model Development

- Implementation of several machine learning models:
  - Logistic Regression
  - Decision Trees
  - Support Vector Machines (SVM)
- Hyperparameter tuning
- Cross-validation

### 4. Model Evaluation

- Accuracy, Precision, Recall, F1-score
- ROC-AUC Curve
- Confusion matrix
- Model comparison

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
