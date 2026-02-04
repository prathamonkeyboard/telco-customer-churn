# Telco Customer Churn Prediction 📉

## 📌 Overview
This project analyzes customer data to identify users likely to cancel their subscription (churn).
Using Python and Machine Learning, I built a model that predicts churn with **78% accuracy**, helping the business focus retention efforts on at-risk customers.

## 💼 Business Problem
Acquiring a new customer is 5-25x more expensive than retaining an existing one. The goal is to predict who will leave so the marketing team can offer incentives to stay.

## 🔍 Key Insights
* **The "Danger Zone":** Customers are most likely to leave in the first 12 months.
* **Price Sensitivity:** Higher monthly charges are strongly correlated with higher churn.
* **Contract Type:** (Optional: If you added this) Month-to-month contracts have the highest churn rate.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Model:** Random Forest Classifier

## 📊 Results
* **Model Accuracy:** 78%
* **Key Achievement:** Successfully identified 46% of actual churners in the test set (Recall), providing a targeted list for retention campaigns.

## 📂 Project Structure
* `01_Data_Cleaning.ipynb`: Raw data processing.
* `02_EDA_and_Modeling.ipynb`: Visualization and Model Training.
* `data/`: Contains raw and processed datasets.
