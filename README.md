# diabetes-predictor
The goal of this project is to create a  process for predicting diabetes by building a machine learning model that analyzes various health parameters. The web application takes user input, processes the data through the model, and provides the prediction result on a new page.
# Technical Aspects
*Machine Learning Model*
**Library:** scikit-learn
**Algorithms Used:** Logistic Regression, Decision Trees, Random Forests (or any chosen algorithms based on your project)
**Input Features:** 
1)Gender 
2)Number of Pregnancies
3)Insulin Level
4)Age
5)Body Mass Index (BMI)
6)Blood Pressure
7)Glucose Level
8)Skin Thickness
9)Diabetes Pedigree Function
**Output:** The model predicts whether the person is likely to have diabetes (Yes/No).
# Web Application
**Framework:** Flask
**Functionality:**
The user provides health-related data via a form.
After submitting the form, the model processes the data and presents the prediction on a new page.

# Prerequisites
Python 3.x
Flask
scikit-learn
Pandas
Heroku CLI (for deployment)
