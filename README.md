# Flipkart CSAT Prediction – Machine Learning Project

## 📌 About
This project focuses on analyzing customer support data and building a machine learning model to predict **Customer Satisfaction (CSAT) scores**.  
The objective is to identify important factors influencing customer satisfaction and evaluate a baseline ML model.

## 📊 Dataset
- **File:** `Customer_support_data.csv`
- Contains customer interaction details, agent information, issue categories, and CSAT scores.

## 🔍 Project Workflow
- Data loading and initial exploration  
- Data cleaning (duplicates, missing values, data types)  
- Exploratory Data Analysis (EDA) using visualizations  
- Feature engineering and feature selection  
- Text preprocessing and TF-IDF vectorization  
- Model training and evaluation  
- Saving the trained model using Joblib  

## 🤖 Machine Learning Model
- **Algorithm Used:** Logistic Regression  
- **Reason:** Simple, interpretable, and suitable as a baseline classification model

## 📈 Evaluation Metrics
The model is evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

A bar chart is used to visualize these metrics.

## 💾 Saved Model
- **File:** `best_model.joblib`  
- The trained model is saved for reuse without retraining.

## ▶️ How to Run
1. Open `Flipcart_Project_ML_Template.ipynb`
2. Run the notebook cells sequentially from top to bottom
3. All outputs, charts, and results will be generated inside the notebook

## 📁 Files in This Repository
- `Flipcart_Project_ML_Template.ipynb` – Main project notebook  
- `Customer_support_data.csv` – Dataset  
- `best_model.joblib` – Saved trained model  

## 🛠 Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- NLTK  

## 👤 Developed By
**Abhishek Yadav**
