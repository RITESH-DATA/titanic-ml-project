🧠 Overview
This project builds a complete end‑to‑end machine learning pipeline to predict passenger survival on the Titanic.
It includes:
• Data cleaning
• Exploratory Data Analysis (EDA)
• Feature engineering
• Multiple ML models
• Model comparison
• Final model selection
• Reproducible notebook workflow
This project is designed as a portfolio‑ready example of practical data science skills.
---
📂 Project Structure

titanic-ml-project/
│
├── data/
│   ├── titanic.csv
│   └── titanic_cleaned.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_model.ipynb
│
├── src/
│   └── titanic_final_model.pkl
│
├── README.md
└── requirements.txt

🧹 1. Data Cleaning
Performed in 01_data_cleaning.ipynb:
• Removed missing values
• Encoded categorical variables
• Created dummy variables for Embarked
• Saved cleaned dataset to data/titanic_cleaned.csv
---
📊 2. Exploratory Data Analysis
Performed in 02_eda.ipynb:
• Survival rate by gender
• Survival rate by passenger class
• Age distribution
• Correlation heatmap
• Feature importance insights
---
🤖 3. Machine Learning Models
Trained in 03_model.ipynb:
Models used:
• Logistic Regression
• Random Forest
• Gradient Boosting

Evaluation metric:
• Accuracy Score

Example comparison:
Logistic Regression: 0.78
Random Forest: 0.84
Gradient Boosting: 0.86

Final model:
Gradient Boosting Classifier
Saved as:
src/titanic_final_model.pkl

🛠 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib

Install with:
pip install -r requirements.txt

🎯 Goal of This Project
This project demonstrates:
• Real‑world data cleaning
• Exploratory analysis
• Multiple ML models
• Model comparison
• Reproducible workflow
• Clear project structure

🚀 Future Improvements
• Add hyperparameter tuning
• Add cross‑validation
• Build a Streamlit web app
• Deploy model with Flask or FastAPI
