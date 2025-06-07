# task-7-bcd
Task 7 – Support Vector Machines (SVM)
Internship: AI and Machine Learning - Binary Classification with SVM
This project implements Support Vector Machines, or SVM, using Scikit-learn to perform binary classification on the Breast Cancer dataset. It includes both linear and non-linear models using the RBF kernel, decision boundary visualizations, hyperparameter tuning, and evaluation with cross-validation.

Dataset
Dataset: Breast Cancer Dataset from Scikit-learn
Target: Binary classification for malignant or benign tumors
Libraries Used
Scikit-learn
Matplotlib
Numpy

Tasks Performed

Loaded the Breast Cancer dataset using Scikit-learn

Preprocessed the features using StandardScaler

Applied PCA to reduce dimensions to two dimensions for visualization

Trained SVM classifiers with both linear and RBF kernels

Visualized decision boundaries for both models

Tuned hyperparameters, specifically C and gamma, using GridSearchCV

Evaluated model performance using confusion matrix, classification report, and cross-validation accuracy


Results

Achieved over ninety-five percent accuracy using both linear and RBF kernels

Found optimal parameters using Grid Search

The RBF kernel performed better after tuning

Visualized clear decision boundaries using PCA components

Important Functions

SVC for Support Vector Classifier

GridSearchCV for tuning C and gamma

cross_val_score for cross-validation performance

PCA for dimensionality reduction for two-dimensional visualization


Output Plots

Linear SVM Decision Boundary

RBF Kernel SVM Decision Boundary
Best SVM Decision Boundary after tuning with RBF kernel
