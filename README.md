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

- Tested KNN values from 1 to 30 using training data.
- Highest mean cross-validation accuracy: approximately **96.3%**.
- Best-performing value: **k = 11**.

**GridSearchCV Hyperparameter Tuning**

- Best parameter: **k = 1**
- Best 5-fold cross-validation accuracy: **95.24%**

**Test Set Evaluation**

- Evaluated the GridSearchCV-selected parameter, **k = 1**.
- Achieved **100% accuracy** on the held-out test set in this experiment.

The manual 10-fold cross-validation and GridSearchCV used different cross-validation settings, which can lead to different optimal values of k.

## How to Run

1. Open `Homework_3_Iris.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure Python, NumPy, Matplotlib, and Scikit-learn are installed.
3. Run the notebook cells in order.
4. Review the cross-validation results, accuracy visualizations, and hyperparameter tuning results.

## Project Background

This project was completed as part of my Computer Science coursework. I independently implemented the assignment using course materials and textbook references.

The project demonstrates practical experience with machine learning classification, model evaluation, cross-validation, hyperparameter tuning, and data visualization.
