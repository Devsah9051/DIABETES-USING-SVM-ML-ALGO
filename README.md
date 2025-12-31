# DIABETES-USING-SVM-ML-ALGO
🩺 Diabetes Prediction using Machine Learning

This project predicts whether a person has diabetes using medical data and machine learning techniques.

📌 About the Project

The goal of this project is to build a machine learning model that can predict diabetes based on patient health information.

📊 Dataset

Dataset: Diabetes dataset (Pima Indians)

Target column: Outcome

0 → No Diabetes

1 → Diabetes

🛠️ Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🔍 Steps Performed

Loaded and explored the dataset

Performed Exploratory Data Analysis (EDA)

Handled missing values (zero values treated as missing)

Applied outlier handling using Z-score capping

Scaled features using StandardScaler

Split data into training and testing sets

Trained machine learning models

Evaluated model accuracy

🤖 Models Used

Logistic Regression (baseline)

Support Vector Machine (SVM)

📈 Model Performance

Train-Test Split: 80% / 20%

Accuracy achieved: ~65%

📂 Project Structure
Diabetes-Prediction-ML/
│
├── diabetes.csv
├── diabetes_prediction.ipynb
└── README.md

✅ Key Learnings

Data preprocessing is very important in medical datasets

Handling missing values improves model performance

Feature scaling is necessary for SVM

Accuracy alone is not always enough to judge a model

🚀 Future Improvements

Hyperparameter tuning

Try advanced models (Random Forest, XGBoost)

Model deployment using Streamlit or Flask

👤 Author

Dev Sah
