Project Title: Logistic Regression Classification – Titanic Dataset

Description
This project implements a Logistic Regression model to predict the survival of passengers aboard the Titanic. The model is trained using passenger details such as age, gender, passenger class, fare, and family information. This project demonstrates the complete machine learning workflow including data preprocessing, feature encoding, model training, and evaluation.

Problem Statement
The Titanic disaster resulted in significant loss of life. Survival chances were influenced by multiple factors such as passenger class, gender, and age. The objective of this project is to build a binary classification model using Logistic Regression to predict whether a passenger survived or not based on available features.

Algorithm Used
Logistic Regression (Supervised Learning – Classification)

Dataset
Titanic Dataset
Source: Kaggle – Titanic: Machine Learning from Disaster

Features Used
Pclass – Passenger class
Sex – Gender
Age – Age of passenger
SibSp – Number of siblings/spouses aboard
Parch – Number of parents/children aboard
Fare – Ticket fare
Embarked – Port of embarkation

Target Variable
Survived (0 – Did not survive, 1 – Survived)

Steps Involved

Load the Titanic dataset

Handle missing values

Encode categorical variables

Split the dataset into training and testing sets

Apply feature scaling

Train Logistic Regression model

Evaluate model performance using accuracy, confusion matrix, and classification report

Results
The Logistic Regression model achieves good accuracy and effectively predicts passenger survival. The results demonstrate that Logistic Regression is suitable for binary classification problems.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
