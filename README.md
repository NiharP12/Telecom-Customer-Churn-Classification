# Telecom Customer Churn Classification

# Project Objective

The objective of this project is to build a machine learning model that can accurately predict whether a telecom customer is likely to churn (leave the service provider). Since customer retention is critical in the telecom industry, the model focuses on minimizing false negatives — ensuring that at-risk customers are correctly identified. The project also explores class imbalance handling using Random Oversampling, and optimizes model performance using GridSearchCV with recall as the primary scoring metric.

# Python and Machine Learning Role

- Python was used as the core programming language for the entire project, enabling clean and efficient implementation of data handling, preprocessing, and modeling.

-  Utilized popular Python libraries such as pandas, numpy, matplotlib, and seaborn for data manipulation and visualization.

- Applied various Machine Learning techniques using scikit-learn, including:

  - Data preprocessing: Label encoding, train-test split.

  - Handling class imbalance using imblearn's RandomOverSampler.

  - Model development: Built and evaluated Random Forest classifiers.

  - Model tuning: Leveraged GridSearchCV to fine-tune Random Forest hyperparameters and optimize for Recall, minimizing false negatives.
 
  - The final model achieves 95% recall using Random Forest with hyperparameter tuning via GridSearchCV. Only 51 false negatives were observed out of 2070 total test cases.

Evaluated model performance using metrics such as Accuracy, Recall, Confusion Matrix, and Classification Report.
