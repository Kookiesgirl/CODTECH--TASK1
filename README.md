NAME : P.VIVISHA CATHERIN
COMPANY : CODTECH IT SOLUTIONS
ID : CT08FJF
DOMAIN : MACHINE LEARNING
DURATION : DECEMBER TO JANUARY 2025

Project Overview: Housing Price Prediction

This project is a simple web application that predicts housing prices based on user-input features like square footage, number of bedrooms, and location. It uses HTML and CSS for the user interface and Python (Flask) for the back-end, which handles the machine learning model.

Key Features:
User Interface (HTML and CSS):

A clean and responsive web form allows users to input:
Square footage.
Number of bedrooms.
Location (currently not fully utilized in the model).
Styling is done with CSS for a professional look.
Back-End (Python Flask):

A Flask server serves the web page and handles form submissions.
Uses a pre-trained Linear Regression model built with scikit-learn to make predictions.
The back-end processes the user input, scales the features, and predicts the price.
Machine Learning:

Uses the Boston Housing dataset to train a Linear Regression model.
Preprocesses the data with scaling (StandardScaler) to ensure features are appropriately normalized.
Splits data into training and testing sets for model evaluation.
Output:

After submitting the form, the predicted housing price is displayed on a new web page.
Project Flow:
User Interaction:

Users visit the web page.
They fill out the form with the required details (square footage, bedrooms, location).
Form Submission:

The data is sent to the Flask server.
Data Processing:

The server processes the input, prepares the features, and scales them.
The scaled features are passed to the pre-trained Linear Regression model.
Prediction and Response:

The model predicts the housing price.
The predicted price is displayed to the user.
Use Cases:
Quickly estimating house prices for small datasets.
Demonstrating the integration of machine learning models with web applications.
Building foundational knowledge in front-end and back-end development.
This project is great for beginners learning:

Front-End: Building web interfaces with HTML and CSS.
Back-End: Setting up a Flask server for handling requests and responses.
Machine Learning: Training and deploying simple predictive models.
