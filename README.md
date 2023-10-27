# Diabetes Prediction using Multi-Classifier Machine Learning Model

This project presents the code/kernel used as a college project assignment.

The aim of this project is to build machine learning multi-classifier models and compare them to be able to determine and select the most optimal machine learning model in predicting diabetes disease.

## About Dataset:
The dataset consists of 9 columns and 768 rows where the columns are:
1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. Blood Pressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skin fold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age (years)
9. Outcome: Class variable (0 or 1)

## About the project:
Several steps were taken to complete this project:
1. Perform Exploritary Data Analysis (EDA) to process data and clean data
2. Clean data is split into 2 parts for training and testing (train 70% test 30%)
3. Create multi-classifier machine learning models consisting of 6 methods including:
   - K-Nearest Neighbor (KNN)
   - Decision Tree
   - Support Vector Machine (SVM)
   - Voting Classifier
   - Random Forest
   - Boosting Classifier
4. Evaluate the level of precision and recall of each model
5. Compare the accuracy scores between one model and another and select the model with the best result
