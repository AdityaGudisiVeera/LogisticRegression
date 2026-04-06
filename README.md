# Employee Turnover Prediction using Logistic Regression

## Overview
This project implements a logistic regression model to predict employee turnover based on various features such as job satisfaction, performance rating, years at company, and more.

## Dataset
- **File**: `employee_turnover.csv`
- **Size**: 1350 rows, 16 columns
- **Features**: Job_Satisfaction, Performance_Rating, Years_At_Company, Work_Life_Balance, Distance_From_Home, Monthly_Income, Education_Level, Age, Num_Companies_Worked, Employee_Role, Annual_Bonus, Training_Hours, Department, Annual_Bonus_Squared, Annual_Bonus_Training_Hours_Interaction
- **Target**: Employee_Turnover (binary: 0 or 1)

## Model
- **Algorithm**: Logistic Regression (from scikit-learn)
- **Train-Test Split**: 80% training, 20% testing (random_state=42)
- **Accuracy**: 86% on test set

## Requirements
- Python 3.x
- Libraries: numpy, pandas, scikit-learn

## How to Run
1. Ensure `employee_turnover.csv` is in the same directory.
2. Open `LogisticRegression.ipynb` in Jupyter Notebook.
3. Run all cells to train the model and evaluate accuracy.



## Notes
- No missing values in the dataset.
- Classes are balanced in the training set.