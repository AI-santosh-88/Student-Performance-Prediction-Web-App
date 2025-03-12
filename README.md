# TITLE: Student Performance Prediction Web App

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


