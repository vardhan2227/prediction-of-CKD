🌟 Chronic Kidney Disease Prediction Using Machine Learning 🌟

(Replace this placeholder with an actual banner image related to your project)

🩺 Introduction
Chronic Kidney Disease (CKD) affects millions worldwide, and early detection is crucial for effective treatment. This project leverages Machine Learning (ML) techniques to predict CKD using real-world data. By combining advanced feature selection methods, balanced datasets, and powerful classifiers, we aim to achieve high-accuracy predictions.

📊 Dataset Overview
Source: UCI Machine Learning Repository
Instances: 400
Attributes: 25
24 features (e.g., Age, Blood Pressure, Hemoglobin).
1 target variable (CKD or Not CKD).
🛠️ Methodology
Data Preprocessing 🚀
Missing values handled using KNN Imputation.
Categorical attributes converted via Label Encoding.
Train-Test Split (50:50) for model evaluation.
Feature Selection 🧪
Full Feature Selection
Correlation-Based Feature Selection (CFS)
Wrapper Feature Selection
LASSO Feature Selection
Machine Learning Classifiers 🤖
Logistic Regression (LR)
Random Forest (RF)
Support Vector Machines (LSVM - L1 & L2 penalties)
Decision Trees (CHAID, C4.5)
K-Nearest Neighbors (KNN)
Artificial Neural Networks (ANN)
Data Balancing with SMOTE 📈
Synthetic Minority Oversampling Technique (SMOTE) was used to balance the dataset and improve model performance.
Evaluation Metrics 🏆
Accuracy, Precision, Recall, F-Measure, AUC, GINI Index, Error Rate
🌟 Key Results
Best Performing Model: Random Forest
Accuracy: 98.49%
Feature Selection Method: LASSO FS with SMOTE
Runner-Up: LSVM (L2 Penalty)
Accuracy: 97.73%
KNN & ANN: Lower performance on this dataset.
🖥️ Tools & Technologies
Programming Language: Python 🐍
Development Environment: Jupyter Notebook 📒
Libraries Used:
Scikit-learn
Pandas
NumPy
Matplotlib
🔮 Future Plans
Investigate undersampling techniques for larger datasets.
Test additional advanced feature engineering methods.
Explore ensemble models for boosting accuracy.
