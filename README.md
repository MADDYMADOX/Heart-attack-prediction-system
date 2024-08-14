Heart Attack Prediction System


Table of Contents
Project Overview
Features
Installation
Usage
Datasets
Model Training
Evaluation
Project Overview
The Heart Attack Prediction System is a machine learning-based tool designed to predict the likelihood of a heart attack based on various medical parameters. This system leverages data analysis and predictive modeling to assist healthcare providers in identifying high-risk patients.

Features
Data Preprocessing: Cleans and prepares the dataset for model training.
Feature Selection: Identifies the most important features influencing heart attack risk.
Machine Learning Models: Implements various models such as Logistic Regression, Random Forest, and XGBoost.
Model Evaluation: Evaluates models using metrics like accuracy, precision, recall, and ROC-AUC.
Web Interface: Simple web application for making predictions based on user input.
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/heart-attack-prediction.git
cd heart-attack-prediction
Create a virtual environment (optional but recommended):

bash
Copy code
python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Train the Model:

bash
Copy code
python train.py
Run the Web Application:

bash
Copy code
python app.py
Access the Application: Open your web browser and go to http://127.0.0.1:5000/.

Make Predictions: Input patient data into the form and submit to receive a heart attack risk prediction.
