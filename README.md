# Logistic-Regression

**Binary and Multiclass Classification with Logistic Regression**
This project demonstrates binary and multiclass classification using logistic regression. It includes predicting insurance purchase decisions and recognizing handwritten digits. Additionally, it involves an exercise on predicting employee retention.

**Binary Classification: Insurance Purchase Prediction**
This section involves predicting whether a customer will buy insurance based on their age.

**Dataset**
The dataset insurance_data.csv contains:
**age:** The age of the customer.
**bought_insurance:** Whether the customer bought insurance (1) or not (0).

**Steps**
**Data Loading and Visualization:**
Loaded the dataset into a DataFrame.
Visualized the data using a scatter plot.

**Model Training:**
Split the data into training and testing sets.
Trained a logistic regression model using the training set.

**Prediction and Evaluation:**
Predicted insurance purchase decisions on the test set.
Evaluated the model's accuracy.
Obtained the probability estimates of the predictions.

**Multiclass Classification: Handwritten Digits Recognition**
This section involves recognizing handwritten digits (0-9) using the Digits dataset from sklearn.

**Dataset**
The Digits dataset contains:
**data:** The pixel values of the digit images.
**target:** The digit labels (0-9).

**Steps**
**Data Loading and Visualization:**
Loaded the Digits dataset.
Visualized some sample images of digits.

**Model Training:**
Split the data into training and testing sets.
Trained a logistic regression model using the training set.

**Prediction and Evaluation:**
Predicted digit labels on the test set.
Evaluated the model's accuracy.
Visualized a specific digit and predicted its label.

**Exercise: Binary Classification for Employee Retention**
This exercise involves predicting whether an employee will leave the company.

**Dataset**
The dataset HR_comma_sep.csv contains various features related to employees, such as:
satisfaction_level
average_montly_hours
promotion_last_5years
salary
left: Whether the employee left the company (1) or not (0).

**Steps**
**Data Loading and Exploration:**
Loaded the dataset into a DataFrame.
Explored the data and calculated the mean of numeric features grouped by the left column.

**Data Visualization:**
Visualized the relationship between salary and left.
Visualized the relationship between Department and left.

**Data Preparation:**
Created dummy variables for the salary column.
Prepared the feature matrix X and target vector y.

**Model Training:**
Split the data into training and testing sets.
Trained a logistic regression model using the training set.

**Prediction and Evaluation:**
Predicted employee retention on the test set.
Evaluated the model's accuracy.

**Dependencies**
pandas
numpy
matplotlib
scikit-learn
word2number
