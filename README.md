# Heart Disease Risk Assessment Application

## Overview
This repository contains a heart disease risk assessment web application that allows users to input their health details and receive predictions on the likelihood of having heart disease. The project uses a machine learning model developed in Python and is deployed using Flask as the web framework.

## Features
- Machine learning model to predict heart disease risk based on user input.
- Flask-based web interface for users to interact with the model.
- Real-time predictions with a simple, user-friendly UI.
  
## Files in the Project
### Main Files:
- **`app.py`**: The Flask web server that handles routes, user input, and model predictions.
- **`model.pkl`**: Serialized machine learning model used to generate predictions.
  
### Folders:
- **`templates/`**: Contains the HTML files for the frontend.
  - **`index.html`**: Form for users to input health data.
  - **`result.html`**: Displays the predicted outcome after form submission.
- **`static/`**: Contains static files like CSS and images.
- **`requirements.txt`**: List of dependencies required for the project.
  
## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-risk-assessment.git
    ```
  
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
  
3. Run the application:
    ```bash
    python app.py
    ```

4. Navigate to the following URL in your web browser:
    ```
    http://127.0.0.1:5000/
    ```

## Dependencies
Make sure to install the necessary libraries listed in `requirements.txt`.

## Model
The machine learning model is trained on a dataset with health attributes such as age, cholesterol, and resting blood pressure, which are used to predict heart disease risk. The trained model is saved
