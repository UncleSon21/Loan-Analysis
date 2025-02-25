# Loan-Analysis
A machine learning project focused on predicting loan defaults. The code explores various of algorithms to identify borrowers who may default on their loans, which is a critical task for financial institutions to manage risk effectively.

# Overview
The project analyzes a dataset of loan information to build predictive models that can identify potential loan defautls. Serveral machine learning algorithms are implemented for a binary classification problem:

- Decision tree classifier
- Random Forest
- Feedforward
- LSTM networks
- Support Vector Machine
- Logistic Regression

# Key features
- Class Imbalance:
  Implemented undersampling of majority class and oversampling of minority class
  Used specialized evaluation metrics (precision, recall, F1, ROC-AUC) appropriate for imbalanced data


- Feature Engineering:
  Created vectorized representations of categorical features (address state, loan purpose, home ownership)
  Transformed and normalized numerical features like loan amount, interest rate, etc.
  Performed feature scaling to improve model convergence


- Model Optimization:
  Conducted grid search for hyperparameter tuning across all models
  Experimented with different architectures for neural networks (varying layers and neurons) and try to use 1D for CNNs.
  Used stratified cross-validation to maintain class distribution across folds
