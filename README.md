# Titanic-Survival-Prediction
Titanic Survival Prediction
This project aims to predict the survival of passengers aboard the Titanic using machine learning 
algorithms. The dataset used for this analysis is the famous Titanic dataset, which contains information 
about passengers such as age, gender, class, fare, etc.
Introduction
This project employs various machine learning techniques to predict whether a passenger survived the 
Titanic disaster. The analysis includes:
Exploratory Data Analysis (EDA)
Preprocessing of Data
Training and Testing of Machine Learning Models
Evaluation of Model Performance
Code Overview
The code is written in Python and utilizes popular libraries such as Pandas, NumPy, Seaborn, and Scikitlearn.
Libraries Used:
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Seaborn: For data visualization.
Scikit-learn: For implementing machine learning models.
Key Steps:
Data Loading and Exploration: The dataset is loaded into a Pandas DataFrame, and basic exploratory 
analysis is performed to understand the structure and characteristics of the data.
Preprocessing: Missing values are handled by imputing mean values for numerical features and 
filling categorical features with appropriate values.
Data Visualization: Seaborn is used to visualize various aspects of the data such as survival rates 
based on different features like age, class, etc.
Model Training and Testing: The dataset is split into training and testing sets. Logistic Regression 
and Support Vector Machine (SVM) models are trained on the training data.
Model Evaluation: The accuracy of the trained models is evaluated using both training and testing 
data.
Prediction: Finally, the trained models are used to predict survival outcomes for new data.
Usage
To run the code, follow these steps:
Clone this repository to your local machine.
Make sure you have Python and the required libraries installed.
Run the provided Python script in your preferred environment.
