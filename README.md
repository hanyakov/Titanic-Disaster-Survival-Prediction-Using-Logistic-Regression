# Titanic-Disaster-Survival-Prediction-Using-Logistic-Regression
This project aims to predict the survival of passengers on the Titanic using logistic regression. The dataset used for this analysis is the famous Titanic dataset, which provides information on the passengers. The goal is to build a machine learning model that can predict whether a passenger survived the disaster based on these features.
Table of Contents
Project Description
Data Description
Data Preprocessing
Model Training and Evaluation
Installation
Usage
Results
Contributing
License
Project Description
This project involves the following steps:

Data Loading: Load the Titanic dataset from a CSV file.
Data Cleaning: Handle missing values and irrelevant columns.
Feature Engineering: Create new features from existing data.
Data Preprocessing: Convert categorical data to numerical values and scale the features.
Model Training: Train a logistic regression model.
Model Evaluation: Evaluate the model using confusion matrix, classification report, and accuracy score.
Data Description
The dataset contains the following columns:

Survived: Survival (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex: Sex
Age: Age in years
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Data Preprocessing
Handling Missing Values:

Fill missing age values with the median age.
Create a new column hasCabin to indicate the presence of cabin information (1 if present, 0 if not).
Feature Engineering:

Convert the Sex column to numerical values using one-hot encoding.
Drop irrelevant columns such as Ticket and Embarked.
Scaling:

Scale the features using StandardScaler.
Model Training and Evaluation
Data Splitting:

Split the data into training, validation, and test sets.
Training:

Train a logistic regression model on the training set.
Evaluation:

Evaluate the model on the validation and test sets using confusion matrix, classification report, and accuracy score.
Installation
To run this project, you need to have Python installed. You can install the required libraries using pip:

