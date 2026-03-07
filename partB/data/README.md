# Dataset Description

This project uses the Breast Cancer Wisconsin dataset available in the scikit-learn library.

Dataset source:
The dataset is loaded using the function:

from sklearn.datasets import load_breast_cancer

This dataset is included directly in the scikit-learn package, so no external download is required.

# Dataset Characteristics

Number of samples: 569  
Number of features: 30  
Task type: Binary classification  

The classification task is to predict whether a tumor is malignant or benign based on several numerical features extracted from cell nuclei images.

# Why This Dataset Was Chosen

The paper selected in Part A focuses on Support Vector Machines and feature selection.  
The Breast Cancer dataset is suitable for this task because:

• It is a classification dataset compatible with SVM models  
• It contains multiple numerical features, making it appropriate for testing feature selection methods  
• It is small enough to run quickly while still demonstrating the behavior of sparse SVM models

# Preprocessing Steps

The following preprocessing steps were applied before training the model:

• Train-test split using an 80/20 ratio  
• Feature scaling using StandardScaler from scikit-learn

Feature scaling is important for SVM models because they are sensitive to the scale of input features.

# Usage in This Project

The dataset is used in the following notebooks:

Task 2.1 – Dataset selection and preprocessing  
Task 2.2 – Implementation of the sparse SVM method  
Task 2.3 – Evaluation and result visualization  
Task 3.1 – Ablation experiments  
Task 3.2 – Failure mode analysis

The dataset is loaded directly inside the notebooks using the scikit-learn API.
