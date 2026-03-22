# fetalhealth_randomforest_classfication
📌 Fetal Health Classification using Random Forest
📖 Overview

This project aims to classify fetal health conditions based on cardiotocography (CTG) data using a Random Forest Classification model. The goal is to assist in identifying fetal health status as Normal, Suspect, or Pathological.

Machine learning is used to analyze various medical features and predict the condition accurately, helping in early diagnosis and decision-making.

🎯 Objective
To build a model that classifies fetal health into three categories:
Normal
Suspect
Pathological
To apply Random Forest Algorithm for multi-class classification
To evaluate the model using performance metrics
🧠 Machine Learning Algorithm
Random Forest Classifier

Random Forest is an ensemble learning method that:

Uses multiple decision trees
Improves prediction accuracy
Reduces overfitting
Handles non-linear data effectively
📂 Dataset
Dataset: Fetal Health Dataset (CTG data)
Features include:
Baseline value
Accelerations
Fetal movements
Uterine contractions
Variability measures
Target Variable:
1 → Normal
2 → Suspect
3 → Pathological
⚙️ Technologies Used
Python
NumPy
Pandas
Matplotlib / Seaborn
Scikit-learn
🚀 Workflow
Data Preprocessing
Load dataset
Handle missing values
Feature scaling (if needed)
Exploratory Data Analysis (EDA)
Visualize feature distribution
Correlation analysis
Data Splitting
Train-Test split (e.g., 80:20)
Model Training
Train using Random Forest Classifier
Prediction
Predict fetal health classes
Evaluation
Accuracy Score
Confusion Matrix
Classification Report
🧪 Model Implementation
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier(n_estimators=100, random_state=42)
model.fit(X_train, y_train)

y_pred = model.predict(X_test)
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
📈 Results
The model achieves strong classification performance
Random Forest effectively handles complex medical data
Helps in distinguishing between fetal health conditions
▶️ How to Run
Clone the repository:
git clone https://github.com/johnlaraji1608-collab/fetalhealth_randomforest_classfication/edit/main/README.md
Navigate to the project:
cd fetal-health-classification
Install dependencies:
pip install -r requirements.txt
Run the script:
python main.py
🔮 Future Improvements
Apply advanced models like XGBoost or Neural Networks
Hyperparameter tuning using GridSearchCV
Deploy as a healthcare web app
Improve interpretability using SHAP
⚠️ Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical advice.


📜 License

This project is open-source and available under the MIT License.
