# Heart-Disease-Prediction

Overview
This project focuses on predicting heart disease using a Logistic Regression model. The key steps involve importing essential libraries, data collection, processing, and splitting, as well as training and evaluating the model's performance.

![image](https://github.com/udaisharma99/Heart-Disease-Prediction/assets/138836370/00f1d67e-eb1f-4e24-9de7-8b4827f74b61)


Libraries Used
NumPy: Utilized for handling numerical data.
Pandas: Employed for working with tabular data.
train_test_split: Utilized to split data into training and testing sets.
LogisticRegression: Implemented to build the Logistic Regression model.
accuracy_score: Used to evaluate the accuracy of the model.

Data Collection and Processing: The dataset, sourced from a CSV file (heart_disease_data.csv), was loaded into a Pandas DataFrame. Initial exploration involved inspecting the first 5 rows, checking data shape, identifying missing values, and performing statistical analysis.

Features and Target Splitting: Features (X) and the target variable (Y) were separated. The distribution of the target variable indicated 165 instances of heart issues and 138 instances of a healthy heart.

Data Splitting: The dataset was split into training and testing sets using the train_test_split function, with 80% for training and 20% for testing.

Model Training: A Logistic Regression model was chosen for its suitability in binary classification. The model was trained on the training dataset.

Model Evaluation: The model's performance was assessed using the accuracy score metric on both training and test datasets, resulting in approximately 85.12% accuracy on training data and 81.97% on test data.

Building a Predictive System: A predictive system was developed to classify individuals as either having or not having heart disease based on input data. The system demonstrated its functionality by correctly identifying a person with heart disease.

Conclusion
This project showcases the implementation of a Logistic Regression model for heart disease prediction, highlighting proficiency in data handling, model training, and evaluation using Python's scikit-learn library.
