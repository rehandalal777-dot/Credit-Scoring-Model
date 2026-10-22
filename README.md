***Credit Scoring Model***

**Project Overview**

This project uses machine learning to predict whether a credit card client is likely to default on their payment. It compares Logistic Regression and Random Forest models and evaluates their performance using classification metrics.

**Objective**

. Predict credit card default.
. Compare different machine learning models.
. Evaluate model performance using Accuracy, Precision, Recall, F1-score, and ROC-AUC.
. Identify important features influencing predictions.

**Dataset**

**UCI Default of Credit Card Clients Dataset**

Source: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

The dataset contains credit card client information, including credit limits, demographic details, repayment status, bill amounts, and previous payment amounts.

**Technologies Used**

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

**Machine Learning Models**

1. Logistic Regression
2. Random Forest Classifier
3. Hyperparameter-tuned Random Forest Classifier using GridSearchCV

**Model Evaluation**

**Model**             |       **Accuracy**     |  **ROC-AUC**
Logistic Regression   |           0.6865       |   0.7162
Random Forest         |           0.7878       |   0.7708
Tuned Random Forest   |           0.7878       |   0.7708

The Random Forest model achieved better overall accuracy and ROC-AUC than Logistic Regression in this experiment. Hyperparameter tuning did not improve the reported test results.

**Important Considerations**

- The dataset contains more non-default than default cases.
- Accuracy alone may not be sufficient for evaluating credit-default predictions.
- The model is an educational project and is not intended for real-world lending decisions.
- Further improvements may include threshold tuning, additional validation, and fairness analysis.

**How to Run**

1. Open the project notebook in Google Colab.
2. Install the required libraries if they are not already available.
3. Run the notebook cells in order.
4. Review the evaluation metrics and feature-importance results.

## Author

GitHub:
[reh andalal777-dot](https://github.com/rehandalal777-dot)
