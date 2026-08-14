# -Code-to-AI-Titanic-survival-prediction-CAPSTONE-PROJECT-
PROHECT CODE TO AI : Titanic Information Files

# Titanic Survival Prediction — Capstone Project

## Problem
Can we predict whether a Titanic passenger survived based on their
class, age, and fare?

## Approach
- Loaded the Titanic dataset (seaborn built-in).
- Cleaned the data: filled missing `age` values with the median,
  selected `pclass`, `age`, and `fare` as features and `survived`
  as the target.
- Split the data 80/20 into training and test sets (`random_state=42`).
- Trained a K-Nearest Neighbors classifier (k=5) on the training data.
- Evaluated the model on the test set using accuracy and a confusion
  matrix.

## Result
The model achieved an accuracy of **[apna number daalein]%** on the
test set. The confusion matrix showed most errors occurred with
passengers who survived but were predicted not to — likely because
key factors like sex and family size weren't included as features.

## Ideas to improve
- Add more features (sex, embarked, family size).
- Try tuning the value of k or testing other algorithms
  (e.g., Logistic Regression, Random Forest).

## Tools used
Python, pandas, seaborn, scikit-learn, matplotlib
