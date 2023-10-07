# Breast Cancer Diagnosis using Machine Learning
Breast cancer is one of the most prevalent and life-threatening diseases among women globally. In this project, the goal is to develop a machine learning solution that can accurately classify breast tumors as either malignant or benign based on a dataset of real-valued features extracted from cell nuclei.

Background:
- Breast cancer is characterized by the presence of abnormal cell growth in breast tissues.
- Biopsy data, including cell nucleus features, can provide valuable information for diagnosing breast
cancer.
- Machine learning models can help automate the diagnosis process, providing quick and accurate
results.

Challenge:
1. ID number: A unique identifier for each biopsy.
2. Diagnosis (M = malignant, B = benign): The ground truth label indicating whether the tumour is
malignant or benign.
3. Ten real-valued features (a to j): Computed measurements from cell nuclei, including
characteristics such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave
points, symmetry, and fractal dimension.

# Model Training 
Before training the data, I used Pandas Library to read and analyse data and dropped the unnecessary input features.

Scikit-learn is an open-source Python library that implements a range of machine learning, pre-processing, cross-validation, and visualization algorithms using a unified interface. Scikit-learn is used for scaling the input features using the StandardScaler() and split the Dataset into training and test datasets using train_test_split().

I used scikit-learn for training the model on the data.csv file using the Logistic Regression algorithm as the breast cancer diagnosis is a Binary Classification Problem where the target lables are either Malignant or Benign (1 or 0).

By Evaluating the Accuracy on Training and Test Datasets, the outcome was as follows:
- Accuracy on training data:  0.989010989010989
- Accuracy on test data:  0.956140350877193
