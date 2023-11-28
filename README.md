# ADNC Severity Prediction: An Interpretable Machine Learning Case Study

## Introduction
This project utilizes machine learning techniques such as Local Interpretable Model-Agnostic Explanations (LIME) and SHapley Additive exPlanations (SHAP) to predict Alzheimer's Disease Neurological Change (ADNC) severity using the dataset from the Seattle Alzheimer's Disease Brain Cell Atlas (SEA-AD) Study.

## Dataset
The dataset, used in this study, is sourced from the [Seattle Alzheimer's Disease Brain Cell Atlas (SEA-AD) Study](https://portal.brain-map.org/explore/seattle-alzheimers-disease/seattle-alzheimers-disease-brain-cell-atlas-download?edit&language=en). It includes donor information, Lumiex data, and quantitative neuropathology summary data.

## Preprocessing
The preprocessing of this dataset includes handling missing values and conducting feature selection. The ADNC target variable was transformed into a binary classification, representing low/intermediate severity and high severity.

## Models
Several machine learning models, including Logistic Regression, Decision Tree Classifier, Gaussian Naive Bayes Classifier, Random Forest Classifier, and others, were trained and evaluated using cross-validation and performance metrics on validation and test sets. 

The Multi-Layer Perceptron (MLP) classifier was selected due to its high performance and its suitability for demonstrating the interpretability of black-box models via LIME and SHAP techniques.

## Results
The MLP model showed high ROC AUC, precision, recall, and F1-score. The model achieved a mean cross-validation score of 91.2%.
