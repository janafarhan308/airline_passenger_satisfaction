# ✈️ Airline Passenger Satisfaction Prediction

## 📌 Project Overview

This project focuses on predicting airline passenger satisfaction using **Machine Learning**.

The main goal is to classify passengers into two categories: **Satisfied** and **Not Satisfied**, based on passenger information and their flight experience.

The project demonstrates a machine learning classification workflow, including data preprocessing, exploratory data analysis (EDA), feature encoding, feature scaling, model training, and evaluation.

## 🎯 Project Objectives

- Explore passenger satisfaction data.
- Identify factors associated with customer satisfaction.
- Clean and preprocess the dataset.
- Visualize relationships between passenger characteristics and satisfaction.
- Build a Logistic Regression classification model.
- Evaluate the model using classification metrics.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset Description

The dataset contains airline passenger information and flight experience ratings.

Examples of features include:

- **Age:** Passenger age
- **Gender:** Passenger gender
- **Customer Type:** Loyal or disloyal customer
- **Type of Travel:** Business or personal travel
- **Class:** Travel class
- **Flight Distance:** Distance traveled
- **Inflight Wi-Fi Service:** Wi-Fi satisfaction rating
- **Seat Comfort:** Seat comfort rating
- **Online Boarding:** Online boarding experience
- **Departure Delay:** Departure delay in minutes
- **Arrival Delay:** Arrival delay in minutes

**Target Variable:** Passenger Satisfaction (Satisfied / Not Satisfied)

## 🔍 Project Workflow

### 1. Data Preprocessing

- Examined dataset structure and data types.
- Handled missing values.
- Encoded categorical features into numerical values.
- Split the dataset into training and testing sets.
- Applied StandardScaler to numerical features for model training.

### 2. Exploratory Data Analysis (EDA)

- Analyzed passenger satisfaction distribution.
- Explored relationships between passenger characteristics and satisfaction.
- Used visualizations to better understand the dataset.

### 3. Model Building

- Used **Logistic Regression** for binary classification.
- Trained the model using the training dataset.
- Predicted satisfaction labels for the testing dataset.

### 4. Model Evaluation

Evaluated the model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📈 Model Performance

| Metric | Result |
|---|---|
| Accuracy | 83.8% |
| True Positives (TP) | 804 |
| True Negatives (TN) | 610 |
| False Positives (FP) | 155 |
| False Negatives (FN) | 119 |

The model achieved approximately **83.8% accuracy**, correctly classifying most passengers in the test dataset.

## 🚀 Future Improvements

- Experiment with Random Forest and XGBoost classifiers.
- Apply cross-validation for more reliable evaluation.
- Perform hyperparameter tuning.
- Explore feature importance and feature selection.
- Compare different classification algorithms.

## 📌 Conclusion

This project demonstrates how Logistic Regression can be applied to predict airline passenger satisfaction.

It highlights the importance of data preprocessing, exploratory analysis, feature scaling, and model evaluation in building a machine learning classification system.
