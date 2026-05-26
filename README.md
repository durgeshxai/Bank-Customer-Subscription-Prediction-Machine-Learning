# Bank Customer Subscription Prediction using Machine Learning

## Project Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on customer demographic details, financial information, and previous marketing campaign interactions.

The project applies the complete Machine Learning workflow including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning Model Building
- Model Evaluation

The main objective is to help banks identify potential customers who are more likely to subscribe to financial products, improving marketing efficiency and customer targeting.

---

# Problem Statement

Banks run marketing campaigns to promote term deposits to customers. Contacting every customer is time-consuming and expensive.

The goal of this project is to build a Machine Learning model that predicts whether a customer will subscribe to a term deposit using historical campaign and customer data.

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Dataset Information

The dataset contains customer-related banking information such as:

- Age
- Job
- Marital Status
- Education
- Account Balance
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Information
- Previous Campaign Outcome
- Subscription Status

## Target Variable

```python
y → Customer Subscription (Yes / No)
Project Workflow
1. Importing Required Libraries

Required Python libraries are imported for:

Data manipulation
Data visualization
Machine learning
Model evaluation
Libraries Used
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Screenshot to Add
Imported libraries section
2. Loading the Dataset

The dataset is loaded into a Pandas DataFrame.

Operations Performed
Reading CSV dataset
Displaying first few rows
Understanding dataset structure
Functions Used
pd.read_csv()
head()
Screenshot to Add
Dataset loading output
First 5 rows of dataset
3. Data Understanding and Exploration

Basic dataset exploration is performed.

Analysis Performed
Dataset shape
Dataset columns
Data types
Statistical summary
Missing values analysis
Functions Used
shape
columns
info()
describe()
isnull().sum()
Screenshot to Add
Dataset information
Describe table
Missing values output
4. Data Cleaning

Data preprocessing is performed to prepare the dataset for Machine Learning.

Cleaning Operations
Handling missing values
Encoding categorical variables
Removing unnecessary columns
Feature transformation
Screenshot to Add
Cleaned dataset output
Encoded dataset output
Exploratory Data Analysis (EDA)

Visual analysis is performed to understand customer behavior and trends.

Visualizations Included
Subscription distribution
Age analysis
Job-wise subscription analysis
Balance analysis
Loan analysis
Marital status analysis
Education analysis
Correlation heatmap
Screenshot to Add
Countplots
Histograms
Heatmap
Bar charts
Feature Engineering

Important features are selected and transformed for model training.

Operations Performed
Feature selection
Label encoding
Train-test split
Feature scaling
Screenshot to Add
Feature engineering output
Train-test split output
Machine Learning Model Building

Machine Learning algorithms are trained to predict customer subscription.

Algorithms Used
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (if used)
Screenshot to Add
Model training output
Prediction results
Model Evaluation

The trained models are evaluated using different performance metrics.

Evaluation Metrics
Accuracy Score
Confusion Matrix
Classification Report
Precision
Recall
F1-Score
Screenshot to Add
Accuracy output
Confusion matrix
Classification report
Key Insights

Some important insights obtained from the analysis:

Customers with higher balances are more likely to subscribe
Previous successful campaigns improve subscription chances
Contact type and campaign duration influence customer conversion
Certain job categories show higher subscription probability
Machine Learning Pipeline
Data Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction System

How to Run the Project
Step 1: Clone the Repository
git clone <your-github-repository-link>
Step 2: Install Required Libraries
pip install -r requirements.txt
Step 3: Open Jupyter Notebook
jupyter notebook
Step 4: Run the Notebook

Open the notebook file and run all cells step by step.

Bank Customer Subscription Prediction(ML).ipynb
