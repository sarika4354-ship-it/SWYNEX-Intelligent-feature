# SWYNEX-Intelligent-feature

## Project Title
AI-Based Student Performance Intelligent Risk Prediction

## Objective
The objective of this project is to build an intelligent feature that predicts whether a student is at academic risk based on performance and engagement-related data.

## Intelligent Feature
The system uses a Decision Tree Classifier to predict student performance risk.

It takes the following inputs:
- Study Hours
- Attendance
- Previous Mark
- Assignment Score

## How It Works
1. Load the student performance dataset.
2. Select the required input features.
3. Split the data into training and testing sets.
4. Train the Decision Tree Classifier.
5. Predict the student's performance category.
6. Calculate model accuracy.
7. Validate user inputs and handle invalid values.

## Error Handling
The system checks for invalid inputs such as:
- Negative values
- Attendance above 100
- Marks above 100
- Invalid input values

If invalid data is provided, the system displays an appropriate error message instead of making a prediction.

## Evaluation
The model is evaluated using Accuracy Score.

Example evaluation result:
- Model Accuracy: 100.0%

## Example Prediction
Example input:
- Study Hours: 3
- Attendance: 65
- Previous Mark: 55
- Assignment Score: 60

Output:
- Prediction: Fail

## Error Handling Example
Input:
- Attendance: 120

Output:
- Error: Marks and attendance must be between 0 and 100.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Decision Tree Classifier
- Google Colab

## Dataset
The project uses the student performance dataset created for the SWYNEX internship project.

## Project Outcome
The intelligent feature demonstrates how machine learning can be used to identify student performance risk and handle invalid inputs safely.

## Internship
This project is completed as part of the **SWYNEX Technologies Internship – Task 3**.
