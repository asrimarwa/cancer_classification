# Classification (Logistic Regression, KNN, Decision Tree)
Using cancer data to predict the probability of a tumor to be malignant, using the following model:
    - Logistic Regression
    - KNN
    - Decision Tree

Feature and target data:
    - Features: 'texture_mean', 'concave points_mean',
    - Target: 'diagnosis'

Use train_test_split validation to find the accuracy of your predictions, with 20% test data and random state 2020.

Determine which is the best model to predict cancer data based on its accuracy?

- Drop missing data if any
- Also try to compare the accuracy results on KNN if with and without scaling (MinMaxScaler)
- Feature description: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

    - diagnosis (M = malignant, B = benign)
    - texture (standard deviation of gray-scale values)
    - concave points (number of concave portions of the contour)
