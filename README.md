# **Breast Cancer Detection Using Support Vector Machine (SVM)**
This project implements a Support Vector Machine (SVM) model to classify breast cancer tumors as malignant or benign. Using the Breast Cancer Wisconsin (Diagnostic) Dataset, we explore SVM's effectiveness in binary classification for medical diagnosis. The model aims to help in identifying cancerous cases accurately, providing valuable support for early intervention.

**Project Overview**


The project focuses on building a supervised machine learning model using an SVM algorithm. SVM is well-suited for classification problems in high-dimensional spaces and can efficiently handle cases where the data is not linearly separable. In this context, we aim to classify tumor samples based on features extracted from cell nuclei images, which can support early breast cancer diagnosis.

**Key Features**


**Data Preprocessing:** 

Cleaning, transforming, and splitting the data into training and test sets.
**Exploratory Data Analysis (EDA):**

Visualizing class distribution and exploring relationships between features to understand data patterns.


**Model Training:** 

Implementing and training an SVM classifier with a linear kernel to achieve initial results.


**Model Evaluation:**

Assessing the model's accuracy, precision, recall, and F1 score to understand its performance.
**Hyperparameter Tuning (Optional):** 

Using GridSearchCV to optimize model parameters for improved performance.


**Dataset**


We use the Breast Cancer Wisconsin (Diagnostic) Dataset from the sklearn library, which contains:
569 samples of tumors, each with 30 features describing characteristics of cell nuclei (e.g., radius, texture, perimeter, smoothness).
Target classes: 0 for malignant tumors and 1 for benign tumors.


**Results**


After training and optimizing the SVM model, the project achieves high accuracy in classifying tumors. The model's performance metrics suggest it is a reliable tool for this binary classification problem, and the use of hyperparameter tuning further enhances its effectiveness.
