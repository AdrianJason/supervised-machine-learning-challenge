# supervised-machine-learning-challenge


This code is a Credit Risk Evaluator that aims to create and compare two models for predicting loan defaults, namely, a Logistic Regression and a Random Forests Classifier.

The code begins by retrieving the data from a CSV file, "lending_data.csv," located in the Resources folder. The Pandas library is used to import the data, and the resulting DataFrame is displayed to confirm the successful import.

After importing the data, the code checks for any missing values and duplicates in the DataFrame. Any duplicates are removed using the drop_duplicates() method. The target variable, "loan_status," is then separated from the features, which are stored in the variable "X."

Next, the data is split into training and testing sets using the train_test_split() method from the scikit-learn library. The random_state parameter is set to 25 to ensure reproducibility.

The code then creates two machine learning models: a Logistic Regression model and a Random Forest Classifier. The Logistic Regression model is created and fitted to the training data using the LogisticRegression() method from scikit-learn. The score for this model is printed to the console.

The Random Forest Classifier is then created and fitted to the training data using the RandomForestClassifier() method from scikit-learn. The score for this model is also printed to the console.

Finally, the code prints which model performed better and how that compares to the author's prediction.

The overall goal of this code is to demonstrate how to compare two machine learning models on a given dataset and to encourage the reader to think critically about which model may perform better on the data.
