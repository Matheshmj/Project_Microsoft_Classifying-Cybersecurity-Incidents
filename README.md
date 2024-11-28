# Project_Microsoft_Classifying-Cybersecurity-Incidents
## Classifying Cybersecurity Incidents
### Overview
The Classifying Cybersecurity Incidents project aims to develop a machine learning model that classifies and categorizes cybersecurity incidents based on various features, such as incident type, severity, attack vector, and more. The goal of this project is to automate the classification of cybersecurity threats, helping organizations identify potential security breaches and vulnerabilities more efficiently.

The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model development, and deployment of the classification model through a user-friendly web application built using Streamlit.
### Key Features
-Data Cleaning & Preprocessing: Handles missing data, removes outliers, and transforms data to improve model performance.
-Exploratory Data Analysis (EDA): Analyzes incident attributes like incident type, severity, source IP address, attack vector, and others to uncover patterns and relationships.
-Model Development: Implements machine learning algorithms (e.g., Random Forest, Logistic Regression, Support Vector Machines) to classify cybersecurity incidents.
-Model Evaluation: Assesses model performance using metrics such as accuracy, precision, recall, and F1-score.
### Technologies Used
-Programming Language: Python
-Libraries & Tools: Pandas,NumPy,Scikit-learn,Matplotlib,Seaborn
-Machine Learning Algorithms: Random Forest,Logistic Regression,Decision Tree Classifier,Xg boost
-Data Visualization: Matplotlib, Seaborn
## Data
The dataset used in this project consists of various features related to cybersecurity incidents, including:

-Incident Type: The type of the cybersecurity event (e.g., phishing, malware, unauthorized access).
-Incident Severity: The severity level of the incident (e.g., low, medium, high).
-Attack Vector: The method used for the attack (e.g., email, network breach).
-Source IP Address: The originating IP address of the attack.
-Target System: The system or service targeted in the incident (e.g., web server, database).
-Date and Time: The timestamp of the incident.
## How It Works
-Data Cleaning: The dataset undergoes cleaning to handle missing values, remove outliers, and drop irrelevant columns. Textual data is converted into numerical representations, and categorical features are encoded appropriately.
-Feature Engineering: New features are generated from the existing data, such as transforming date-time into weekday and hour, and encoding attack vectors into numerical formats.
-Model Training: Several machine learning models are trained on the cleaned data to classify incidents into predefined categories based on various features.
-Model Evaluation: Models are evaluated based on metrics such as accuracy, precision, recall, and F1-score to determine the best-performing model.
## Model Performance
The performance of different machine learning models is evaluated using key metrics: Accuracy, Macro-F1 Score, Precision, and Recall. Below is a comparison of the models:

Logistic Regression:

Accuracy: 0.91
Macro-F1 Score: 0.76
Precision: 0.80
Recall: 0.73
Decision Tree:

Accuracy: 0.97
Macro-F1 Score: 0.91
Precision: 0.90
Recall: 0.92
Random Forest:

Accuracy: 0.99
Macro-F1 Score: 0.98
Precision: 0.98
Recall: 0.98
Best Model Based on Macro-F1 Score
XGBoost:

Accuracy: 0.99
Macro-F1 Score: 0.97
Precision: 0.97
Recall: 0.97
