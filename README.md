# Heart Disease Prediction using Decision Tree and Random Forest

## Description

This project predicts the presence of heart disease in patients based on various health metrics using machine learning algorithms. The dataset used for this project is the *Heart Disease Dataset*, and two models are applied for prediction:

1. *Decision Tree Classifier*
2. *Random Forest Classifier*

The dataset is split into training and testing sets to evaluate model performance, and the accuracy of both classifiers is calculated and compared.

## Prerequisites

Before running the code, you need to install the required Python libraries. Install the dependencies using the following command:

```bash
pip install pandas scikit-learn


Required Libraries:
pandas: For data manipulation and analysis.
scikit-learn: For machine learning models and evaluation metrics.


Dataset
The dataset (heart.csv) should contain health-related attributes such as age, sex, blood pressure, cholesterol levels, etc., along with a target column indicating the presence or absence of heart disease.

Make sure that the heart.csv file is located in the same directory as the script, or update the file path accordingly.

How to Run the Script
Place the heart.csv dataset in the same directory as the Python script.
Run the script to train the Decision Tree and Random Forest classifiers.
The script will print the accuracy scores for both models.

Example of the CSV File
The CSV file should have the following columns:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Serum Cholesterol
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate Achieved
Exercise Induced Angina
ST Depression
Slope of the Peak Exercise ST Segment
Number of Major Vessels (0-3) Colored by Fluoroscopy
Thalassemia
Target (1 = presence of heart disease, 0 = absence
