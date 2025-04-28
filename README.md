# Predictive-Diabetes
Diabetes Prediction
This project focuses on building a highly accurate machine learning model to predict diabetes in individuals based on diagnostic health parameters. After thorough data cleaning, preprocessing, and exploratory data analysis (EDA), two advanced models were trained and evaluated, achieving strong predictive performance.

Table of Contents
Overview

Dataset

Workflow

Libraries Used

Modeling

Results

Overview
Diabetes is a major global health concern. This project aims to predict diabetes early using machine learning techniques. The focus was on achieving high accuracy through careful preprocessing, EDA, and model selection.

Dataset
Source: diabetes

Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Target:

Outcome (0 = Non-Diabetic, 1 = Diabetic)

Workflow
Data Loading: Imported dataset using Pandas.

Data Cleaning:

Replaced zero values in critical columns (e.g., Glucose, BloodPressure) with appropriate strategies.

Handled missing and invalid entries.

Exploratory Data Analysis (EDA):

Visualized distributions and relationships.

Identified feature importance.

Preprocessing:

Standardized feature values.

Handled imbalances if necessary.

Modeling:

Built and trained multiple models.

Focused on tuning for high accuracy.

Libraries Used
Python

Pandas

Numpy

Matplotlib

Seaborn

Scikit-learn


Modeling
Split dataset into training and testing sets.

Models Trained:

Gradient Boosting Classifier: 91.45% accuracy

Support Vector Machine (SVM): 90.79% accuracy


Classification Report (Precision, Recall, F1-Score)

Accuracy Score

Results

Model	Accuracy (%)

Gradient Boosting Classifier	91.45
Support Vector Machine (SVM)	90.79
✅ Gradient Boosting Classifier performed best and was selected as the final model.
