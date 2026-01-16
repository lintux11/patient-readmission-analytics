Patient Readmission Analytics (ML + SQL + Python)

This project analyzes hospital patient records and builds a machine learning model to predict whether a patient is likely to be readmitted. It focuses on real-world healthcare analytics steps like data cleaning, feature engineering, model evaluation, and threshold tuning.

What this project does:
Loads and explores hospital readmission dataset
Performs data validation and exploratory data analysis (EDA)
Encodes categorical features using one-hot encoding
Trains ML models to predict patient readmission
Evaluates performance using accuracy, precision, recall, F1-score and confusion matrix
Tunes classification threshold to balance precision vs recall for healthcare use cases

Tech Stack:
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook, Matplotlib, Key ML Models Used, Logistic Regression (baseline), Random Forest Classifier (improved performance)

Results Summary:
Achieved baseline accuracy around 60%
Performed threshold tuning to improve recall for high-risk readmission detection
Compared model performance using classification metrics and confusion matrix
Why this matters (Healthcare context)
Predicting readmissions helps hospitals improve patient care, reduce avoidable re-admissions, and optimize resource planning.

How to Run:
1. Clone the repository:
   git clone https://github.com/lintux11/patient-readmission-analytics.git
   cd patient-readmission-analytics

   
 2.Create virtual environment and install dependencies:
   python3 -m venv .venv
   source .venv/bin/activate
   pip install pandas numpy scikit-learn matplotlib

   
 3.Open notebook
    code .
 Run (readmission.ipynb)



Folder Structure:
Notebooks/ → Jupyter notebook for full workflow
Data/ → Dataset used for training and analysis

Next Improvements:
Add ROC-AUC and PR-AUC evaluation,
Hyperparameter tuning using GridSearchCV,
Feature importance visualization,
Deploy as a small FastAPI prediction service,
