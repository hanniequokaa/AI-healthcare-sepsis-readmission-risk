*Hospital Readmission Prediction*

This project uses machine learning to predict whether a patient will be readmitted to the hospital within 30 days. It follows a complete AI development workflow, from data preprocessing to model evaluation and saving for deployment.

*Project Overview*

The goal of this project is to assist hospitals in identifying patients at high risk of readmission. By predicting this early, medical staff can provide additional care and reduce preventable readmissions.

*AI Development Workflow*

Data Preprocessing:
Loaded and cleaned the dataset (hospital_readmissions.csv).

Handled missing values and encoded categorical features.
Split data into training and test sets.

Model Development:
Trained a Logistic Regression model to predict readmission.
Tuned hyperparameters to improve accuracy.

Model Evaluation:
Evaluated using accuracy, precision, recall, and confusion matrix.
Visualized performance with a confusion matrix plot.

Model Deployment:
Saved the trained model as readmission_model.pkl for integration into hospital EHR systems.

*Files Included*

File	Description
patient-readmission-risk.ipynb	Main notebook with code for preprocessing, training, and evaluation
hospital_readmissions.csv	Dataset used for model training
readmission_model.pkl	Saved trained model
README.md	Project overview and documentation
report.pdf	Final report including workflow reflection and diagram

*How to Run*
Install dependencies:
pip install pandas scikit-learn matplotlib
Open the notebook:
jupyter notebook patient-readmission-rsk.ipynb
Run all cells to train and evaluate the model.

*Reflection*
The most challenging part was ensuring the model handled missing and categorical data correctly. With more time, hyperparameter tuning and feature engineering could improve prediction accuracy.
# AI-healthcare-sepsis-readmission-risk
