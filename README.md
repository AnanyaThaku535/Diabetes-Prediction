# Diabetes-Prediction
roject Overview

The Diabetes Prediction System is a Machine Learning-based desktop application built using Python, Logistic Regression, and Tkinter GUI.
The goal of this project is to predict whether a person is diabetic, prediabetic, or non-diabetic based on key health indicators such as BMI, blood pressure, cholesterol level, age, and lifestyle habits.

This project combines data science and user-friendly design to help users understand their health risks through an interactive graphical interface.

⚙️ Technologies Used

Python – Core programming language

Pandas, NumPy – Data preprocessing and manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn (sklearn) – Model building and evaluation

Tkinter – GUI for user interaction

Pickle / Joblib – Model serialization (saving and loading trained models)

🧩 Features

✅ Load and clean diabetes dataset
✅ Train Logistic Regression model on health data
✅ Evaluate accuracy and visualize results with graphs
✅ Predict diabetes category (0 = No Diabetes, 1 = Prediabetes, 2 = Diabetes)
✅ GUI-based interface for easy user input and prediction
✅ Personalized recommendations based on results

📊 Dataset

Dataset Name: diabetes_012_health_indicators_BRFSS2015.csv
Source: Centers for Disease Control and Prevention (CDC) – Behavioral Risk Factor Surveillance System (BRFSS 2015)

🚀 How It Works

Load the dataset and preprocess it.

Select key health-related features.

Train a Logistic Regression model to classify diabetes risk.

Evaluate model performance using accuracy, confusion matrix, and classification report.

Save the trained model using pickle.

Build a Tkinter-based GUI for user-friendly interaction.

Take input from users, scale it, and predict the result instantly.

🧮 Model Performance

Algorithm: Logistic Regression (One-vs-Rest Multiclass)

Accuracy: ~80–85% (depending on dataset split)

Evaluation Metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-score

🖥️ GUI Preview

The GUI provides fields to input data like HighBP, HighChol, BMI, Age, etc., and predicts the diabetes category with health recommendations.
