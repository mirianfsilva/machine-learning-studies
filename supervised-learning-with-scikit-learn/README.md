## Supervised Machine Learning

- Predict Variables/features and a target variable.
- Aim: Predict the target variable, given the predictor variables.

The goal of supervised learning is frequently to either automate a time-consuming or expensive manual task. 
Need labeled data: historical data with labels, experiments to get labeled data, crowd-sourcing labeled data. 

Some exploratory data analysis using toy datasets from scikit-learn:

- **Classification**: Target variable consists of categories. 
    - Iris sample data exploratory; 
    - Digits sample data exploratory;
- **Regression**: Target variable is continuous. 
    - Boston sample data exploratory;
    

### Notes: 
Topics explained in [Classification | Data exploration using iris toy dataset](https://github.com/mirianfsilva/machine-learning-studies/blob/master/supervised-learning-with-scikit-learn/classification-data-exploratory.ipynb)

- Constructing a classifier using **K-Nearst Neighbors (KNN)** algorithm;
- Using scikit-learn to fit a classifier;
- Predicting on unlabeled data;
- Measuring model perfomance;
- Train/Test split;
- Model Complexity

-----------
Topics explained in [Regression | Data exploration using boston housing dataset](https://github.com/mirianfsilva/machine-learning-studies/blob/master/supervised-learning-with-scikit-learn/regression-data-exploratory.ipynb)

- Creating features and target values;
- Fitting a regression model;
- The Basics of Linear Regression:
    - Regression mechanics;
- Linear Regression on all features;
- Cross-validation:
    - Cross-validation motivation;
    - Cross-validation and model performance;
    - K-Fold CV comparison;
- Regularized Regression:
    - Ridge Regression;
    - Lasso Regression;
        - Lasso regression for feature selection;

-----------
Topics explained in [Fine Tuning your Model](https://github.com/mirianfsilva/machine-learning-studies/blob/master/supervised-learning-with-scikit-learn/fine-tuning-your-model.ipynb)

- Classification Metrics;
- Diagnosing classification predictions;
- Metrics from the Confusion Matrix: 
    - Precision;
    - Recall;
    - F1-score;
- Logistic regression and the ROC curve:
    - Logistic regression for binary classification;
    - Probability thresholds;
    - The ROC curve and area under the ROC curve;
- Hyperparameter Tuning;
- Choosing the correct hyperparameter;

