#📊 Multiple Linear Regression – Insurance Premium Prediction

This project demonstrates the implementation of Multiple Linear Regression to predict insurance charges based on key features such as age, BMI, region, gender, smoker status, and number of children. The dataset used is publicly available and processed to create a clean and standardized model pipeline.

📂 Project Overview

The goal of this project is to:

Explore and understand the Insurance Premium Dataset.

Perform data cleaning, exploratory data analysis (EDA), and feature engineering.

Apply standardization and encode categorical variables.

Build and evaluate a Multiple Linear Regression model using scikit-learn.

🧰 Technologies & Libraries

This project is built using:

Python 3.x

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

📊 Dataset

The dataset contains information about insurance premium charges along with attributes like:

Age: Age of the insured person

Sex: Gender (Male/Female)

BMI: Body Mass Index

Children: Number of dependents

Smoker: Whether the person is a smoker (Yes/No)

Region: Residential region

Charges: Medical insurance charges (Target variable)

Dataset Source:
Insurance Premium Dataset

⚡ Project Workflow

Data Loading
Load the dataset directly from the GitHub repository using pandas.

Data Exploration & Cleaning

Check for missing values, data types, and basic statistics.

Identify unique values in categorical columns.

Visualize gender distribution using Seaborn’s countplot.

Feature Engineering

Standardize continuous variables (age, bmi, charges) using StandardScaler.

Encode categorical variables (sex, smoker, region) with pd.get_dummies.

Train-Test Split

Split data into 80% training and 20% testing using train_test_split.

Model Building

Fit a LinearRegression model on training data.

Calculate model intercept and R² scores for both train and test sets.
