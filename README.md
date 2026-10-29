# Iris Classification — KNN Hyperparameter Tuning

## Project Overview

This project uses Python and Scikit-learn to classify iris flower species using the K-Nearest Neighbors (KNN) machine learning algorithm.

The objective is to explore how different values of `k` (the number of nearest neighbors) affect classification accuracy and to evaluate model performance using cross-validation and hyperparameter tuning.

## Technologies Used

- Python
- Scikit-learn
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Features

- Loaded the Iris dataset using Scikit-learn.
- Implemented a K-Nearest Neighbors classification model.
- Evaluated values of `k` ranging from 1 to 30.
- Applied 10-fold cross-validation to compare model accuracy.
- Calculated mean accuracy and standard deviation for different hyperparameter values.
- Visualized classification accuracy using Matplotlib.
- Used GridSearchCV with 5-fold cross-validation for automated hyperparameter tuning.
- Evaluated a KNN model using a separate test dataset.

## Results

**Initial 10-Fold Cross-Validation**

The highest mean cross-validation accuracy was **98%**, achieved with several values of `k`, including 13, 18, and 20.

**GridSearchCV Hyperparameter Tuning**

- Best parameter identified: `k = 1`
- Best cross-validation accuracy: **95.24%**

**Test Set Evaluation**

A separately trained KNN model using `k = 13` achieved **100% accuracy** on the test split in this experiment.

The initial cross-validation analysis and GridSearchCV evaluation used different data configurations, so their accuracy scores should not be interpreted as directly comparable.

## How to Run

1. Open `Homework_3_Iris.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure Python, NumPy, Matplotlib, and Scikit-learn are installed.
3. Run the notebook cells in order.
4. Review the cross-validation results, accuracy visualizations, and hyperparameter tuning results.

## Project Background

This project was completed as part of my Computer Science coursework. I independently implemented the assignment using course materials and textbook references.

The project demonstrates practical experience with machine learning classification, model evaluation, cross-validation, hyperparameter tuning, and data visualization.
