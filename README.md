# Bank Loan Prediction Deployment

This project focuses on predicting the approval status of bank loans using a Decision Tree machine learning model. The model is trained on historical data and deployed on AWS to enable real-time predictions through a user-friendly web application.

Overview

Loan approval is a critical process in the banking sector. This project automates the decision-making process using a trained Decision Tree model to classify loan applications as Approved or Rejected.

The project is deployed on AWS, making it accessible for real-time predictions via a REST API and a web interface.

Features

Predict loan approval based on applicant details such as income, loan amount, and credit history.
Deployed on AWS for scalability and accessibility.
User-friendly web application interface.
API endpoints for programmatic predictions.

Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Flask, Boto3, Matplotlib, Seaborn

Deployment Platform: AWS (EC2, S3, Elastic Beanstalk)

Model Algorithm: Decision Tree

Frontend Framework: Streamlit

Architecture

Model Training:

Train a Decision Tree model on historical loan application data.
Save the trained model as a .pkl file.

AWS Deployment:

Model Storage: The trained model is stored in an S3 bucket.
API Hosting: Flask API is hosted on AWS Elastic Beanstalk.
Web Application: A Streamlit-based web interface is deployed on an AWS EC2 instance.

Setup and Installation

Prerequisites

AWS account with necessary permissions for EC2, S3, and Elastic Beanstalk.
Python 3.7 or above installed locally.
AWS CLI configured locally.
 
Model Training
The Decision Tree model was trained using the following pipeline:

Data Cleaning: Handle missing values and outliers.

Feature Engineering: Encode categorical features, normalize numerical features.

Model Building: Train a Decision Tree classifier using Scikit-learn.

Model Evaluation: Evaluate using metrics such as Accuracy, Precision, Recall, F1-Score.

Future Enhancements

Implement advanced tree-based algorithms (Random Forest, XGBoost) for better accuracy.
Add CI/CD pipelines for automated deployment.
Integrate monitoring tools to track model performance in production.

Contributors

Chinmayee Tingne
