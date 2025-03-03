# Building-a-Model-for-Predicting-Death-Events-Due-to-Heart-Failure-Using-Decision-Tree

## Overview
This project aims to develop a classification model using a Decision Tree to predict whether a patient will die during the follow-up period based on a dataset containing medical records of heart failure patients. The dataset consists of various clinical features that contribute to the prediction of death events.

## Dataset
The dataset contains information about patients who experienced heart failure, collected during their follow-up period. The key features include:
- Age
- Serum Creatinine
- Ejection Fraction
- Platelets
- Creatinine Phosphokinase
- Serum Sodium
- High Blood Pressure
- Anaemia
- Diabetes
- Smoking
- Time (Follow-up period)
- Death Event (Target Variable: 0 = Survived, 1 = Deceased)

## Objective
The goal is to build and evaluate a Decision Tree classifier that predicts the "Death Event" based on patient data.

## Steps to Build the Model
1. **Data Preprocessing:**
   - Load the dataset
   - Handle missing values (if any)
   - Perform exploratory data analysis (EDA)
   - Compute feature correlations

2. **Train-Test Split:**
   - Split the data into training and testing sets (80:20 ratio) using `train_test_split()` **without setting a random state**

3. **Model Training:**
   - Train a Decision Tree classifier using the default hyperparameters

4. **Model Evaluation:**
   - Evaluate model performance on the training data
   - Evaluate model performance on the test data using accuracy, precision, recall, and F1-score

5. **Experimentation:**
   - Train multiple (5-7) models without a fixed random state to observe variations
   - Compare model performance across different runs

6. **Hyperparameter Tuning:**
   - Adjust hyperparameters (e.g., max depth, min samples split) to improve model performance

## Tools & Libraries
- **Python**
- **Pandas** for data manipulation
- **Seaborn & Matplotlib** for visualization
- **Scikit-learn** for machine learning model development

## Expected Outcomes
- Identification of key clinical features influencing heart failure mortality.
- A well-performing Decision Tree model capable of predicting death events with high accuracy.
- Insights into how different train-test splits impact model performance.

## Future Improvements
- Experimenting with other classification models (Random Forest, Logistic Regression, etc.).
- Feature engineering to enhance predictive accuracy.
- Implementing cross-validation for more robust model evaluation.

---

### Author
Developed by [Your Name] as part of a machine learning project on medical data analysis.

