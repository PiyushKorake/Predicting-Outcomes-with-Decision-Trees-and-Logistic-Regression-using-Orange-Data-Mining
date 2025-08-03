# Predicting Outcomes with Decision Trees and Logistic Regression using Orange

## Overview
This project explores two machine learning models built using Orange Data Mining. The first model is a Decision Tree that predicts whether Sara will go sailing based on weather and other factors. The second is a Logistic Regression model that classifies Iris flower species. We also tried both models on a wine dataset to see how well they perform.

## Objectives
- Use a Decision Tree to predict binary outcomes
- Use Logistic Regression to classify multi-class data
- Evaluate models using accuracy, precision, recall, and F1-score
- Manually complete the confusion matrix tasks
- Understand model behavior using Orange’s visual interface

## Datasets Used
1. **Sailing dataset** – to predict if Sara will sail
2. **Iris dataset** – to classify flower species
3. **Wine dataset** – to compare model performance on a new domain

## Tools
- Orange Data Mining (no coding required)
- Built-in evaluation and visualization tools in Orange
- Manual calculation of confusion matrices and probabilities

## Model Details

### Decision Tree Model (Sailing)
- Input: Weather, Company, Sailboat size
- Output: Will Sara sail? (Yes/No)
- Training Accuracy: ~73%
- Test Accuracy: ~60%
- AUC: 0.667
- Insights:
  - Sunny weather and company increase sailing chances
  - Rainy days usually mean Sara won’t sail

### Logistic Regression Model (Iris)
- Input: Sepal and Petal measurements
- Output: Iris class (Setosa, Versicolor, Virginica)
- Accuracy: Perfect on test data
- Petal length and width were the most important features

### Wine Dataset Classification
- Decision Tree: 80% accuracy, 100% recall for Type 3 wines
- Logistic Regression: 90% accuracy, high scores across all types
- Logistic Regression performed better overall

## Key Learnings
- Decision Trees are easy to interpret and good for simple binary tasks
- Logistic Regression works well for multi-class classification
- Orange is helpful for beginners to understand ML concepts through drag-and-drop interfaces

## Author
Piyush Santosh Korake  
