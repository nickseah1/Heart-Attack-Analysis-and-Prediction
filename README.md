# Heart-Attack-Analysis-and-Prediction

#Introduction

The purpose of this project is to build a machine learning model to predict a person's change of a heart attack.


# Data Description

## Categorical Features
* sex - Gender of person
* cp - Chest pain type
* caa - number of major vessels (0-3)

* fbs - fasting blood sugar (fbs > 120 mg/dl) (1 = true, 0 = false)
* restecg - resting electrocardiographic results 

    (0:normal, 1:ST-T wave abnormality, 2:showing probable or definite left ventricular hypertrophy by Estes' criteria)

* exng - exercise induced angina (1= yes, 0 = no)
* slp - slope
* thall - thal rate

## Continuous Features

* trtbps - Resting blood pressure (mm Hg)
* chol - cholesterol in mg/dl fetched via BMI sensor
    (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic)
    
* Age - Age of person
* thalachh - maximum heart rate achieved
* oldpeak - previous peak



## Target
* output - target variable (0 = less chance of heart attack, 1 = more chance of heart attack)
