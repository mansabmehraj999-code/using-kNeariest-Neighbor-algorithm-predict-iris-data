Project Introduction
This notebook demonstrates the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset. It covers data loading, preprocessing, visualization, model training, testing, and evaluation in Python.

Library Imports
The notebook imports pandas, numpy, matplotlib, and scikit-learn datasets for building the model.

Dataset Loading
The Iris dataset is loaded from scikit-learn into a pandas DataFrame. Features include sepal length, sepal width, petal length, and petal width. The target is the class label encoded as integers, with a mapped flower name for better understanding.

Exploratory Data Analysis and Visualization
Initial data samples and class distributions are displayed. Data points are separated by flower species. Scatter plots visualize feature relationships colored by class, helping to observe separability.

Data Preparation for Modeling
Features (excluding target and flower names) are selected as input variables. Target labels are kept as output. The dataset is split into training and testing sets with an 80-20 ratio using a random seed for reproducibility.

Building and Training the KNN Model
The KNN classifier is initialized with a k-value of 5 neighbors. The model is fitted using the training data.

Model Testing and Prediction
Model accuracy is calculated on the test data. Predictions are generated for evaluation.

Results and Evaluation
Classification metrics such as precision, recall, F1-score, and accuracy are computed. Note: For multiclass problems, metrics require specifying an appropriate average method like 'macro' or 'weighted' to avoid errors.

Error Handling
Address possible exceptions when computing metrics on multiclass targets by setting the average parameter correctly.

Extra Section
The notebook briefly includes loading the California Housing dataset, but it is not used in the KNN classifier workflow.

Conclusion
This notebook provides a complete pipeline from data loading to model evaluation for the KNN algorithm on the Iris dataset. It is educational for understanding KNN basics and evaluation in Python.
