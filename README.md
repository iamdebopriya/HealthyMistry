Disease Prediction System
A Streamlit-based application that predicts diseases based on user-reported symptoms. The app provides predictions along with detailed information about the disease, including precautions, medications, diet recommendations, and workouts.

Features
Symptom Selection: Users can select symptoms from a list.
Disease Prediction: The app predicts the most likely disease based on the selected symptoms.
Detailed Information: Provides disease description, precautions, medications, diet recommendations, and workouts.
Technologies Used
Python
Streamlit for the web application framework
Scikit-learn for the machine learning model
Pandas for data handling
NumPy for numerical operations
Files
app.py: Main Streamlit application file
symtoms_df.csv: CSV file with symptoms data
precautions_df.csv: CSV file with precautions data
workout_df.csv: CSV file with workout data
description.csv: CSV file with disease descriptions
medications.csv: CSV file with medications data
diets.csv: CSV file with diet data
svc.pkl: Pickle file with the trained machine learning model
