credit-card-fraud-detection-system
📌 Project Overview
This project focuses on analyzing credit card transactions to identify fraudulent activities and understand transaction risk patterns using Python, Data Analysis, and Machine Learning.

The dataset used is the famous Credit Card Fraud Detection dataset from Kaggle.

The project includes:

Data preprocessing
Exploratory Data Analysis (EDA)
Fraud detection insights
Risk level classification
Linear Regression model
Data visualization using Matplotlib, Seaborn, and Plotly
🚀 Features
✅ Data Cleaning and Duplicate Removal
✅ Fraud vs Normal Transaction Analysis
✅ Risk Level Classification
✅ Statistical Analysis
✅ Correlation Heatmap
✅ Interactive Visualizations
✅ Linear Regression Model
✅ Residual Analysis
✅ Export Cleaned Dataset
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn
KaggleHub
📂 Dataset
Dataset Source: Credit Card Fraud Detection Dataset from Kaggle

path = kagglehub.dataset_download("mlg-ulb/creditcardfraud")
📊 Exploratory Data Analysis
The project includes multiple visualizations such as:

Fraud vs Normal Transactions
Transaction Amount Distribution
Boxplots for Outlier Detection
Time vs Amount Scatter Plot
Correlation Heatmap
Risk Level Distribution
⚠️ Risk Level Classification
Transactions are categorized based on amount:

Amount Range	Risk Level
< 100	Low Risk
100 - 999	Medium Risk
≥ 1000	High Risk
🤖 Machine Learning Model
A Linear Regression model is used to predict transaction amounts based on transaction time.

Model Evaluation Metrics
R² Score
Mean Squared Error (MSE)
📈 Visualizations
Interactive charts are created using Plotly:

Pie Chart
Histogram
Scatter Plot
Bar Chart
📁 Output
The cleaned dataset is exported as:

cleaned_creditcard_dataset.csv
▶️ How to Run the Project
1️⃣ Install Required Libraries
pip install kagglehub plotly pandas numpy matplotlib seaborn scikit-learn
2️⃣ Run the Notebook / Script
python fraud_detection.py
📌 Project Workflow
Import Libraries
Load Dataset
Data Cleaning
Exploratory Data Analysis
Risk Classification
Model Training
Model Evaluation
Data Visualization
Export Dataset
📷 Sample Insights
Fraud transactions are extremely rare compared to normal transactions.
High-value transactions have higher fraud probability.
Transaction amount distribution is highly skewed.
🎯 Future Improvements
Implement Logistic Regression
Use Random Forest / XGBoost
Build Real-Time Fraud Detection System
Deploy with Streamlit or Flask
Add Deep Learning Models
