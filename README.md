# TITLE: Student Performance Prediction Web App

## problem statement:"To develop a user-friendly web application that accurately predicts a student's potential academic performance (measured as a percentage of marks) based on the number of hours they dedicate to studying daily. This application should provide a quick and accessible way for students to estimate the impact of their study habits on their potential grades, and it should store input and prediction data for future analysis."

## Description:
* This project creates a simple web application using Flask that predicts a student's potential marks percentage based on the number of hours they study per day. The application utilizes a pre-trained machine learning model (likely a regression model) to make these predictions. Users input the study hours through a web form, and the application displays the predicted percentage. Additionally, it stores the input and predicted data in a CSV file for record-keeping.

## Responsibilities:
### Front-End Interaction:
* Create a user-friendly HTML form (index.html) to collect study hours input.
* Display the prediction results to the user on the same page.
### Back-End Processing:
* Develop a Flask application to handle user requests.
* Receive input data from the HTML form.
* Validate the input to ensure it's within a reasonable range (0-24 hours).
* Load the pre-trained machine learning model.
* Use the model to predict the student's marks percentage.
* Format and display the prediction results.
* Store the input and output in a pandas dataframe and then save to a csv file.
### Data Management:
* Store input and predicted data in a Pandas DataFrame.
* Save the DataFrame to a CSV file ('smp_data_from_app.csv') for data persistence.
### Model Integration:
* Load and utilize a pre-trained machine learning model (Desktop.pkl).

## Libraries:
### 1.Flask: 
* For creating the web application.
### 2.NumPy:
* For numerical operations and array manipulation.
### 3.Pandas: 
* For data manipulation and storage (DataFrame, CSV).
### 4.Joblib: 
* For loading the pre-trained machine learning model.

## Summary:
* This project builds a basic web application that allows users to predict student performance based on study hours. It leverages Flask for the web interface, NumPy and Pandas for data handling, and Joblib to deploy a pre-trained machine learning model. The application provides a simple prediction service and stores input/output data for future analysis.


