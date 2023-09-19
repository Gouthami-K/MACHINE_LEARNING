# Diabetes Prediction using Machine Learning
Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Symptoms of high blood sugar include frequent urination,
increased thirst, and increased hunger. If left untreated, diabetes can cause many complications. Acute complications can include diabetic ketoacidosis, hyperosmolar 
hyperglycemic state, or death. Serious long-term complications include cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. 
Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima 
Indian heritage.

# Objective
We will try to build a machine learning model(logistic regression) to accurately predict whether the patients in the dataset have diabetes or not.

# Details about the dataset:
## Dataset
- We used the [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?select=diabetes.csv) for this project.
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: Diabetes pedigree function

Age: Age (years)

Outcome: Class variable (0 or 1)
Number of Observation Units: 768

# Variable Number: 
9

# EDA and preprocessing
Basic data exploration.
Data visualization and analysis to gain insights into the dataset.
Handled missing values and outliers.
Scaled numerical features
 

# Result:
The performance of themodel was evaluated using various metrics, including accuracy, precision, recall, F1-score, and ROC-AUC.
