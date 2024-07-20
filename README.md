## Student Performance Analysis

**Project Overview**
This project aims to analyze student performance data and provide predictions through a web application. The analysis includes exploratory data analysis (EDA) and model training for predicting student performance. The project involves the following components:

Exploratory Data Analysis (EDA)
Model Training
Flask Web Application
Deployment to AWS using CI/CD

**Notebooks Description**
*1. EDA STUDENT PERFORMANCE.ipynb*
This notebook covers the following steps:

Data Loading: Load the student performance dataset.
Data Cleaning: Handle missing values, correct data types, and remove duplicates.
Exploratory Data Analysis (EDA): Visualize the data to identify trends and patterns. Key steps include:
Descriptive statistics
Correlation analysis
Visualizations (e.g., histograms, box plots, scatter plots)
Feature Engineering: Create new features based on domain knowledge to improve model performance.

*2. MODEL TRAINING.ipynb*
This notebook includes the following steps:

Data Preprocessing: Prepare the data for modeling, including:
Tokenization
Stop words removal
Lemmatization
Vectorization using TF-IDF
Model Training: Train machine learning models to predict student performance. The primary model used is Logistic Regression.
Model Optimization: Use GridSearchCV to tune model hyperparameters for optimal performance.
Model Evaluation: Evaluate the model's performance using appropriate metrics (e.g., accuracy, precision, recall).

*Flask Web Application*
The Flask web application provides an interface for users to input student data and receive performance predictions. The app includes:

1. User Interface: A form to input student data.
2. Model Integration: Backend integration to use the trained model for predictions.
3. API Endpoints: RESTful API endpoints to handle data submission and return predictions.

*Deployment to AWS using CI/CD*
The project is deployed on AWS using Continuous Integration and Continuous Deployment (CI/CD) pipelines. The deployment process includes:

1. CI/CD Pipeline: Automated build, test, and deployment using tools like GitHub Actions or Jenkins.
2. AWS Services: Deployment of the Flask application on AWS Elastic Beanstalk or EC2 instances.
3. Docker: Containerization of the application using Docker for consistent deployment.

*Setup Instructions*
To run this project locally, follow these steps:

1. Clone the repository or download the project files.
2. Ensure you have Python installed on your system (preferably version 3.8 or higher).
3. Install the necessary libraries by running the following command:

pip install -r requirements.txt

4. Set up AWS credentials and configure your AWS CLI.
5. Run the Flask application locally:
flask run

6. To deploy the application to AWS, follow the deployment instructions in the deployment/README.md file.

*Requirements*
Python 3.8 or higher
Jupyter Notebook or JupyterLab
Flask
AWS CLI
Docker
CI/CD tools (e.g., GitHub Actions, Jenkins)
Libraries listed in requirements.txt (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn)
