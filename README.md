# Customer Churn Prediction

Binary classification project predicting customer churn from a Kaggle
dataset. Compares several classifiers and picks the best-performing one.

## Contents
- `kaggle-asg-2.ipynb` — end-to-end notebook: EDA, preprocessing,
  model training, evaluation.

## Models compared
Logistic Regression, K-Nearest Neighbors, SVC, Random Forest, Gradient
Boosting, AdaBoost, Bagging, XGBoost — tuned with `GridSearchCV`.

## Run

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter
jupyter notebook kaggle-asg-2.ipynb
```
