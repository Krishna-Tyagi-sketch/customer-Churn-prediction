# customer-Churn-prediction
Customer Churn Prediction Using Random Forest

Project Overview

This project uses Machine Learning to predict whether a customer is likely to leave a service (customer churn). A Random Forest Classifier is used to learn patterns from customer data and classify customers based on their likelihood of churning.

The goal is to demonstrate a complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, and performance evaluation.

Objectives

* Analyze customer data to identify patterns associated with churn.
* Clean and preprocess the dataset before model training.
* Train a Random Forest classification model.
* Evaluate model performance using classification metrics.
* Understand factors that may contribute to customer churn.

Dataset

* Dataset size: 7,043 rows × 21 columns
* Target variable: Churn
* Problem type: Binary classification
* Dataset source:https://drive.google.com/file/d/1Qlj4AoKqbMq3CuGcxA0veMbpKLk42cpv/view

The target variable indicates whether a customer has churned.

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

Remove any library or tool that you did not actually use.

Project Workflow

1. Data Loading: Imported the customer dataset.
2. Data Preprocessing: Prepared the dataset for machine learning, including applicable missing-value handling and categorical-variable encoding.
3. Exploratory Data Analysis (EDA): Examined the data to understand customer characteristics and churn patterns.
4. Feature Preparation: Prepared input features and the target variable.
5. Train-Test Split: Split the dataset into training and testing subsets.
6. Model Training: Trained a Random Forest Classifier.
7. Evaluation: Evaluated the model using classification metrics.

Machine Learning Model

Algorithm: Random Forest Classifier

Random Forest combines predictions from multiple decision trees to perform classification. It can model nonlinear relationships and interactions between customer features.

Model Performance

The following results were recorded during project development. Confirm that the values and metric format match your notebook before publishing them.

Metric	Result
Accuracy	79%*
Precision	78%*
Recall	79%*
F1-score	78%*

*Assuming your original values of 0.79, 0.78, 0.79, and 0.78 are decimal scores equivalent to 79%, 78%, 79%, and 78%, respectively.

How to Run the Project

1. Clone or download this repository.
2. Install the required libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Load the dataset and update its file path if necessary.
5. Run the notebook cells in order to reproduce the analysis, model training, and evaluation.

Install the main libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn

Key Learnings

* Data preprocessing and feature preparation.
* Exploratory data analysis.
* Training a Random Forest classification model.
* Evaluating classification performance using multiple metrics.
* Understanding how machine learning can support customer-retention analysis.

Krishna Tyagi

* GitHub: Krishna-Tyagi-sketch
