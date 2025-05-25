# Diabetic Prediction using Machine Learning

This project implements a Diabetes Prediction System using machine learning techniques. It uses the **Pima Indians Diabetes Dataset** to predict whether a person is diabetic based on medical data.

# 🧠 Model Overview

- Algorithm Used: Support Vector Machine (SVM) with linear kernel
- Features Used:
  - Number of pregnancies
  - Glucose level
  - Blood pressure
  - Skin thickness
  - Insulin level
  - BMI
  - Diabetes Pedigree Function
  - Age

# 📁 Files

- `diabetic_prediction.py` – Python script for loading data, preprocessing, training the model, and making predictions.
- `diabetes - diabetes.csv` – Dataset (make sure to include or update the path in the script).

# 🚀 How to Run

# Requirements

Make sure you have Python installed. Install required packages:
pip install numpy pandas scikit-learn

Steps:
Clone the repository or download the files.
Ensure the CSV file is in the correct path or update the path in the script:
diabetes_dataset = pd.read_csv('diabetes - diabetes.csv')
Run the script:
python diabetic_prediction.py

📊 Output
The script prints:
Dataset info
Training and test accuracy
Prediction result for a custom input

Example:
Accuracy score of the training data :  0.79
Accuracy score of the test data :  0.77
The person is diabetic

📌 Notes
Data is standardized using StandardScaler.

You can replace the input_data variable with new values to test different cases.

🛠 Future Improvements
Add a GUI or web interface for user input

Expand to other classifiers and compare results
Deploy as a web service using Flask or FastAPI
