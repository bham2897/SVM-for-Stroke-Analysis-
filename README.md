# SVM-for-Stroke-Analysis-

**Overview**

The script aims to build an SVM model to categorize individuals into different stroke risk levels. It involves several key steps:

Data loading and preprocessing
Feature scaling
Model training and prediction
Evaluation of model performance
Visualization of ROC curves and confusion matrices

**Dataset**

The dataset used in this project is Final_Preprocessed_data.csv, which contains preprocessed features relevant to stroke risk prediction. The dataset is split into training and test sets to evaluate the model's performance.

**Features**

The dataset includes various features relevant to stroke risk. The exact nature and number of these features depend on the preprocessed dataset provided.

**Model**

The model used is an SVM classifier from scikit-learn, chosen for its effectiveness in classification tasks.

**Performance Metrics**

The model's performance is evaluated using the following metrics:

Precision
F1 Score
Accuracy
ROC (Receiver Operating Characteristic) curve
AUC (Area Under the Curve)
Confusion Matrix
Visualization

The script generates two types of visualizations:

ROC Curve: Plots the true positive rate against the false positive rate at various threshold settings.
Confusion Matrix: Visualizes the model's performance in terms of true positives, true negatives, false positives, and false negatives.
Requirements

