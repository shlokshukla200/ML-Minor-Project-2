# 📊✨ Multiple Linear Regression – Insurance Premium Prediction

This project showcases the implementation of Multiple Linear Regression to predict insurance charges based on key factors such as Age, BMI, Region, Gender, Smoker Status, and Number of Children.
The dataset used is publicly available and carefully processed to create a clean & standardized model pipeline.

📂 Project Overview

The goal of this project is to:

🔍 Explore & understand the Insurance Premium dataset.

🧹 Perform data cleaning, exploratory data analysis (EDA), and feature engineering.

⚙️ Apply standardization and encode categorical variables.

🤖 Build & evaluate a Multiple Linear Regression model using scikit-learn.

🧰 Technologies & Libraries

This project is built using:

🐍 Colab

🔢 NumPy

🏷️ Pandas

📊 Matplotlib

🎨 Seaborn

⚡ Scikit-learn

📈 Dataset Details

The dataset contains information about insurance premium charges with the following attributes:

👤 Age: Age of the insured person

🚻 Sex: Gender (Male/Female)

⚖️ BMI: Body Mass Index

👨‍👩‍👧 Children: Number of dependents

🚬 Smoker: Whether the person is a smoker (Yes/No)

🌍 Region: Residential region

💵 Charges: Medical insurance charges (Target variable)

📌 Dataset Source: Insurance Premium Dataset

⚡ Project Workflow

Here’s the step-by-step process followed:

1️⃣ Data Loading

📥 Load the dataset directly from the GitHub repository using pandas.

2️⃣ Data Exploration & Cleaning

🔎 Check for missing values, data types, and basic statistics.

🧩 Identify unique values in categorical columns.

📊 Visualize gender distribution using Seaborn’s countplot.

3️⃣ Feature Engineering

📏 Standardize continuous variables (Age, BMI, Charges) using StandardScaler.

🏷️ Encode categorical variables (Sex, Smoker, Region) with pd.get_dummies.

4️⃣ Train-Test Split

✂️ Split data into 80% training and 20% testing using train_test_split.

5️⃣ Model Building

⚡ Fit a LinearRegression model on the training data.

🧮 Calculate model intercept and R² scores for both train and test sets.

✨ With this approach, you can accurately predict insurance charges based on multiple real-world features! 🚀
