# HealthCareProjects
Data Science Projects - Healthcare Domain

Healthcare - Diabetes Prediction
This project focuses on predicting diabetes in patients using machine learning techniques. The dataset used is the PIMA Indian Diabetes Dataset from Kaggle, which includes the following predictor variables:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
The target variable is:

Outcome: Class variable (0 or 1), where 268 of 768 entries are 1 (indicating diabetes) and 500 of 768 entries are 0 (indicating no diabetes).
This is a binary classification problem. The initial process involves exploratory data analysis (EDA) and data preprocessing, which includes understanding the dataset through various techniques such as viewing the head of the dataset, its shape, column types, information, and summary. Data cleaning is also performed to handle duplicates, null values, and invalid zero values.

Next, the data is split into training and testing sets. Multiple models are trained and evaluated, including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, and Random Forest. Model comparison is performed using metrics such as confusion matrix, accuracy rate, misclassification rate, and ROC AUC score.

The best model is identified based on the highest accuracy rate and ROC AUC score. In this project, the SVM model was selected as the best model with an accuracy score of 83.1% and an ROC AUC score of 0.79. This model is then used to make predictions on new data.
