Student Performance Prediction – Machine Learning Project
A simple and beginner-friendly Machine Learning project that predicts a student's Final Exam Score based on:
Hours Studied
Attendance (%)
Previous Exam Score
This project uses Linear Regression to build the prediction model.

Project Overview
This project demonstrates the basic steps of building a supervised ML model:
Loading and exploring a dataset
Data preprocessing
Selecting features and target
Training a Linear Regression model
Evaluating performance
Saving the model

The dataset contains the following columns:
Feature	Description
Hours_Studied	Number of hours studied per day
Attendance	Attendance percentage
Previous_Score	Previous exam score
Final_Exam_Score	Target variable to predict

Dataset file: student_performance.csv
 Machine Learning Model
Algorithm used: Linear Regression
Libraries:
pandas
scikit-learn
joblib
Model file: student_performance_model.pkl
Model Accuracy
Achieved R² Score:
0.99+ (Excellent performance)

How to Run the Notebook
Open the .ipynb file in Google Colab or Jupyter Notebook
Run all cells
Train the model

Make predictions using the model
Files in this Repository
├── student_performance.csv
├── student_performance_model.pkl
├── your_notebook.ipynb
└── app.py  (optional Streamlit UI)

 Future Improvements
Use more advanced ML models (Random Forest, XGBoost)
Add more features to improve accuracy
Deploy on HuggingFace / Streamlit Cloud
Add visualizations in the notebook

 Author
Ramakrishnan — AI & Data Science Student
