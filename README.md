# Customer-Churn-Prediction-and-Risk-Segmentation

📌 Project Overview
Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom companies, streaming platforms, and SaaS products. Losing existing customers directly impacts revenue and growth.
This project builds an end-to-end Customer Churn Prediction pipeline using a real-world telecom dataset. The system analyzes customer behavior, predicts churn probability using Machine Learning models, segments customers into churn-risk categories, and visualizes insights through interactive dashboards.
The goal is not only to build an accurate ML model, but also to generate business-friendly insights that help companies proactively retain customers.

🎯 Objectives
Analyze customer behavior and churn patterns
Perform Exploratory Data Analysis (EDA)
Build and compare multiple classification models
Predict whether a customer will churn
Segment customers into:
High Risk
Medium Risk
Low Risk
Visualize churn insights using Plotly/Streamlit
Generate actionable business recommendations

🧠 Problem Statement
Subscription-based businesses lose significant revenue every year due to customer churn — customers who cancel or stop using a service.
Predicting which customers are likely to churn before they actually leave allows businesses to:
Offer retention discounts
Improve customer support
Personalize communication
Increase customer lifetime value
This project simulates a real-world analyst workflow followed by product and growth teams.

📂 Dataset Information
The project uses a telecom customer dataset containing customer demographics, account information, subscription details, billing history, and churn labels.
Example Features
Feature
Description
gender
Customer gender
SeniorCitizen
Whether customer is senior citizen
tenure
Number of months with company
MonthlyCharges
Monthly bill amount
TotalCharges
Total amount charged
Contract
Contract type
InternetService
Type of internet service
PaymentMethod
Payment mode
Churn
Target variable (Yes/No)
⚙️ Project Workflow
Plain text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Churn Prediction
      ↓
Risk Segmentation
      ↓
Dashboard Visualization

📊 Exploratory Data Analysis (EDA)
Performed detailed EDA to identify churn trends and customer behavior patterns.
Key Analyses
Churn distribution
Contract type vs churn
Monthly charges analysis
Tenure distribution
Payment method analysis
Correlation heatmaps
Customer segmentation trends
Visualization Tools
Matplotlib
Seaborn
Plotly

🛠️ Data Preprocessing
The following preprocessing techniques were applied:
Handling missing values
Encoding categorical variables
Feature scaling
Removing duplicates
Converting target labels into binary format

🧪 Feature Engineering
Created meaningful business-oriented features such as:
Tenure groups
Average customer spend
Contract duration categories
Service usage patterns
Customer value indicators

🤖 Machine Learning Models Used
The following classification models were trained and compared:
Model
Purpose
Logistic Regression
Baseline interpretable model
Decision Tree
Rule-based classification
Random Forest
Ensemble learning
XGBoost
Gradient boosting
Support Vector Machine (SVM)
Boundary-based classification

📈 Model Evaluation Metrics
Models were evaluated using:
Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix
Special focus was placed on Recall, since missing potential churn customers can result in revenue loss.

🚨 Churn Risk Segmentation
Customers were segmented based on predicted churn probability.
Risk Tier
Churn Probability
High Risk
> 80%
Medium Risk
40% – 80%
Low Risk
< 40%
This helps businesses prioritize retention campaigns efficiently.

📉 Dashboard & Visualization
An interactive dashboard was created using:
Plotly
Streamlit
Dashboard Features
Customer churn overview
Interactive filters
Churn risk visualization
Model performance metrics
Customer segmentation analysis

💡 Key Business Insights
Some important findings from the analysis:
Customers with month-to-month contracts churn more frequently
High monthly charges are associated with increased churn
Long-tenure customers are less likely to leave
Fiber internet users showed higher churn behavior
Electronic check payment users had higher churn probability

✅ Business Recommendations
Based on the analysis:
Offer loyalty incentives to high-risk customers
Encourage long-term contracts through discounts
Improve support for fiber internet users
Create personalized retention campaigns
Monitor high monthly charge customers proactively

🧰 Technologies Used
Python
Libraries
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Plotly
XGBoost

📁 Project Structure
Bash
Customer-Churn-Prediction/
│
├── data/
│   └── telecom_churn.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── dashboard/
│   └── app.py
│
├── images/
│   └── dashboard_screenshots/
│
├── requirements.txt
├── README.md
└── LICENSE
🚀 How to Run the Project
1️⃣ Clone the Repository
Bash
git clone https://github.com/your-username/customer-churn-prediction.git
2️⃣ Navigate to Project Folder
Bash
cd customer-churn-prediction
3️⃣ Install Dependencies
Bash
pip install -r requirements.txt
4️⃣ Run Dashboard
Bash
jupyter notebook

📌 Future Improvements
Deploy model on cloud platform
Add real-time churn prediction
Integrate automated email retention campaigns
Use Deep Learning models
Add explainable AI (SHAP/LIME)

📚 Learning Outcomes
This project demonstrates:
Data Analysis
Feature Engineering
Machine Learning
Classification Modeling
Business Interpretation
Dashboard Development
Customer Analytics
