# Mini Project on Machine Learning: Predicting FWI (Fire Weather Index) using Algeria Forest Fire Dataset
This repository contains the code and resources for a mini project that aims to predict the Fire Weather Index (FWI) using Algeria Forest Fire data. The project utilizes Linear Regression and is implemented as a web application using Python Flask, HTML, CSS, and other technologies.

You can access the deployed web app here: https://algeria-forest-fire.onrender.com/

# Project Overview

# Purpose
The primary goal of this project is to predict the Fire Weather Index (FWI) for Algeria based on historical forest fire data. The FWI is a critical metric for assessing fire danger in a given area and is valuable for fire management and prevention.

# Technologies Used
    - Python for machine learning model development
    - Flask for building the web application
    - HTML and CSS for the frontend
    - Linear Regression for predictive modeling
    - Jupyter Notebook for data analysis and model development

# Data
The dataset used for this project contains historical records of forest fires in Algeria, including various weather and environmental variables. These records are used to train the Linear Regression model.

# Getting Started
 To run the project locally, follow these steps:
 
    Clone this repository to your local machine.

# bash
git clone https://github.com/your-username/algeria-forest-fire-prediction.git

    Navigate to the project directory.

# bash
cd algeria-forest-fire-prediction

    Create a virtual environment and activate it (optional but recommended).

# bash
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

    Install the project dependencies.
# bash
pip install -r requirements.txt

    Run the Flask application.

# bash

python application.py

    Open a web browser and access the web application at http://localhost:5000.

# Project Structure

The project directory is organized as follows:

php

├── application.py               # Flask web application code
├── static/              # Static assets (CSS, images, etc.)
├── templates/           # HTML templates
├── data/                # Dataset used for model training
├── models/              # Trained machine learning models
├── notebooks/           # Jupyter notebooks for data analysis and model development
├── requirements.txt     # Project dependencies
├── README.md            # Project documentation

# Model Training

The machine learning model used for FWI prediction is trained using the provided dataset. You can explore the model development process and analysis in the Jupyter notebooks located in the notebooks/ directory.

# Contributions
Contributions to this project are welcome. If you want to make improvements, fix issues, or add new features, please create a pull request.
