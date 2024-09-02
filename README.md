Fraud Detection Model

Overview

This project involves building a fraud detection model using a financial transactions dataset. The model is designed to predict fraudulent transactions, helping financial institutions to identify and prevent fraud. The project employs data cleaning, handling class imbalance, removing multicollinearity, and feature normalization. A logistic regression model is used to predict whether a transaction is fraudulent or not.


Install Dependencies: Navigate to the project directory and install the required Python packages using:


pip install -r requirements.txt

Download the Dataset: The dataset used for this model can be accessed from the following drive link: Download Dataset
(Replace the # with the actual drive link to your dataset)

Prepare the Data: Place the downloaded dataset in the appropriate directory as expected by the code. By default, the script expects the data to be named fraud_data.csv and to be in the project root directory.

Run the Model Script: Execute the model training script to preprocess the data, train the model, and evaluate its performance:


python fraud_detection.py

Evaluate Results: After running the script, check the output for the confusion matrix, classification report, accuracy, and ROC-AUC score to understand the model's performance.

How It Works

Data Cleaning: 

The script handles missing values, removes outliers using the IQR method, and addresses multicollinearity using the Variance Inflation Factor (VIF).

Feature Normalization: 

Normalizes features using StandardScaler after handling class imbalance.
Model Training: Uses logistic regression to train the model, applying class weights to handle any imbalance.
Evaluation: 

The model's performance is evaluated using accuracy, ROC-AUC score, confusion matrix, and classification report.

Note

The dataset required for training the model is not included in this repository due to size constraints. Please download the data from the link provided below.

https://drive.google.com/drive/folders/1bcRZ7mjQb5KTwFETTU57yQ8AK27JRaex?usp=drive_link
