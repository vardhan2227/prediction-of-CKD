### Chronic Kidney Disease Prediction Using Machine Learning
### Introduction
Chronic Kidney Disease (CKD) is a severe health condition requiring early detection for effective treatment. This project leverages Machine Learning (ML) techniques to predict CKD using real-world data. By applying feature selection, data balancing, and various ML classifiers, we aim to achieve highly accurate predictions.

### Dataset Overview
Source: UCI Machine Learning Repository, 

Instances: 400,

Attributes: 25,

24 features (e.g., Age, Blood Pressure, Hemoglobin).

1 target variable: CKD or Not CKD.

### 🛠️ Methodology

1. Data Preprocessing 🚀
Missing Value Handling: KNN Imputation.
Categorical Conversion: Label Encoding.
Train-Test Split: 50:50 for evaluation.

2. Feature Selection Techniques 🧪:-
Full Feature Selection, 
Correlation-Based Feature Selection (CFS), 
Wrapper Feature Selection, 
LASSO Feature Selection.

3. Machine Learning Classifiers 🤖:-
Logistic Regression (LR)

Random Forest (RF)

Support Vector Machines (LSVM - L1 & L2 penalties)

Decision Trees (CHAID, C4.5)

K-Nearest Neighbors (KNN)

Artificial Neural Networks (ANN)

5. Data Balancing 📈
SMOTE (Synthetic Minority Oversampling Technique): Ensures balanced datasets for better predictions.

6. Evaluation Metrics 🏆
Accuracy, 
Precision, 
Recall, 
F-Measure, 
Area Under Curve (AUC), 
GINI Index, 
Error Rate.

### Key Results
Best Performing Model: Random Forest

Accuracy: 98.49%

Feature Selection Method: LASSO FS with SMOTE.

Runner-Up Model: LSVM (L2 Penalty)

Accuracy: 97.73%.

Observation: KNN and ANN did not perform well with this dataset.

### Technologies Used
Language: Python 🐍

Environment: Jupyter Notebook 📒 

### Libraries:
Scikit-learn

Pandas

NumPy

Matplotlib

### Future Plans
Explore undersampling techniques for larger datasets.

Investigate advanced feature engineering methods.

Experiment with ensemble models to boost accuracy further.

