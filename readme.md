Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

What Are We Doing?

We are evaluating various machine learning models to detect fraudulent credit card transactions.

Models Used:
    Logistic Regression
    Decision Tree
    Random Forest
    Gradient Boosting

Model Performance Comparison:
                 Model  Training Accuracy  Test Accuracy       AUC
0  Logistic Regression           0.958069       0.944162  0.979489
1        Decision Tree           1.000000       0.908629  0.908576
2        Random Forest           1.000000       0.918782  0.980468
3    Gradient Boosting           1.000000       0.923858  0.983199

Best Estimator: Logistic Regression

Why Logistic Regression?

Logistic Regression is selected as the best estimator because it demonstrates similar training and test accuracy, indicating that the model is neither overfitting nor underfitting

Tech Stack: Python(Pandas, Numpy, Scikit-learn, Seaborn)
