# Random Forest Classification – Airline Customer Satisfaction Prediction

## Project Overview

This project applies **Machine Learning Classification techniques** to predict airline customer satisfaction using the **Random Forest Classifier**.

The main objective is to build, optimize, and evaluate a classification model that can identify whether an airline customer is satisfied or dissatisfied based on customer service, flight experience, and demographic features.

The project demonstrates the complete machine learning workflow including:

- Data cleaning
- Feature preprocessing
- Three-way data splitting
- Hyperparameter optimization using GridSearchCV
- Model evaluation
- Comparison with Decision Tree Classification

---

# Project Objectives

The objectives of this project are:

- Load and explore the airline satisfaction dataset
- Handle missing data
- Encode categorical variables
- Split data into training, validation, and testing datasets
- Apply Random Forest Classification
- Tune model parameters using GridSearchCV
- Use PredefinedSplit for validation control
- Evaluate model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Compare Random Forest performance with Decision Tree
- Interpret the results

---

# Dataset Description

The dataset contains airline customer information and feedback related to flight experiences.

Example features include:

| Feature | Description |
|---|---|
| Age | Customer age |
| Gender | Customer gender |
| Customer Type | Type of customer |
| Flight Distance | Distance travelled |
| Seat Comfort | Rating of seat comfort |
| Food and Drink | Food service rating |
| Inflight Service | Quality of inflight service |
| Online Boarding | Online boarding experience |
| Satisfaction | Target variable |

The target variable is:
