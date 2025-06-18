# Heart-Attack-Prediction-ML-Auto-ML
Heart attack risk prediction using traditional ML models and H2O AutoML on clinical data.

🫀 Heart Attack Prediction using Machine Learning and AutoML (H2O)
📌 Project Overview
This project aims to predict the likelihood of a heart attack using various machine learning models and an automated ML framework — H2O AutoML. The goal is to build a reliable and interpretable system that can assist in early identification of heart disease risk based on patient health parameters.

🎯 Objective
To develop and compare traditional ML models with H2O's AutoML tool to:

Predict heart attack chances based on clinical data

Improve accuracy and model efficiency

Identify the most important risk factors (features)

🗃️ Dataset Details
Source: [Kaggle / UCI Heart Disease Dataset]

Rows: 303

Columns: 14 features (age, sex, chest pain type, cholesterol, blood pressure, etc.)

Target Variable: target (1 = heart disease, 0 = no heart disease)

🧪 Tools & Technologies Used
Languages: Python

Libraries:

Pandas, NumPy (Data manipulation)

Matplotlib, Seaborn (EDA and visualization)

Scikit-learn (ML algorithms)

H2O AutoML (automated ML training and leaderboard)

Environment: Google Colab

🔍 Exploratory Data Analysis (EDA)
Performed EDA to understand:

Distribution of heart attack risk across gender and age groups

Correlation between features like cholesterol, blood pressure, and heart attack

Outlier analysis and missing value handling

📊 Models Used
✅ Traditional ML Models:
Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

Support Vector Machine

🤖 AutoML Model:
H2O AutoML Leaderboard used to find the best model automatically from:

GBM, XGBoost, Deep Learning, Stacked Ensembles, etc.

🏆 Best Performing Model
Model Name: Stacked Ensemble (from H2O AutoML)

Accuracy: 87.5%

AUC Score: 0.92

Feature Importance: Age, Chest Pain Type, Cholesterol, etc.

📌 Key Takeaways
AutoML (H2O) can automatically select the best model and hyperparameters

Traditional models like Random Forest and Gradient Boosting also performed well

Combining domain knowledge with AutoML gives strong results

📂 Project Structure
bash
Copy
Edit
📁 Heart_Attack_Prediction/
├── Heart_attact_Prediction.ipynb   # Jupyter notebook with all code
├── README.md                       # Project documentation
├── requirements.txt                # Python libraries
