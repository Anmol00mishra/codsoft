# codsoft
CODSOFT Data Science Internship projects – Titanic Survival Prediction, Iris Flower Classification, and Credit Card Fraud Detection. Includes notebooks, datasets, results, and insights from model evaluation.
# CODSOFT Data Science Internship 🚀

This repository contains the projects completed during my **CODSOFT Data Science Internship**.  
Each task explores different domains of machine learning – classification, multiclass classification, and imbalanced data handling.  

---

## 📂 Tasks

### 🔹 Task 1 – Titanic Survival Prediction 🚢
**Problem:** Predict survival of Titanic passengers based on features like age, sex, class, fare, etc.  
**Approach:**  
- Data preprocessing (missing values for Age, Embarked, Cabin)  
- Feature engineering: FamilySize, IsAlone, Title  
- Models: Logistic Regression, Random Forest  
**Results:**  
- Logistic Regression Accuracy: ~81%  
- Random Forest Accuracy: ~84%  
- ROC-AUC: ~0.88  
**Insights:** Female passengers & 1st class travelers had higher survival chances.

---

### 🔹 Task 2 – Iris Flower Classification 🌸
**Problem:** Classify iris flowers into Setosa, Versicolor, Virginica using sepal & petal measurements.  
**Approach:**  
- Encoded species labels, standardized features  
- Models: SVM (RBF kernel), KNN (k=7)  
**Results:**  
- SVM Accuracy: ~97%  
- KNN Accuracy: ~95%  
**Insights:** Setosa perfectly separable; Versicolor & Virginica overlap → misclassifications occur there.

---

### 🔹 Task 3 – Credit Card Fraud Detection 💳
**Problem:** Detect fraudulent transactions from highly imbalanced credit card dataset.  
**Approach:**  
- Stratified split to preserve class imbalance  
- Models: Logistic Regression (class_weight=balanced), Random Forest (balanced_subsample)  
- Metrics: Precision, Recall, F1-score, ROC-AUC  
**Results:**  
- Logistic Regression ROC-AUC: ~0.94  
- Random Forest ROC-AUC: ~0.98  
**Insights:** Accuracy is misleading for imbalanced data; Recall is critical; Random Forest performed best.

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 📌 How to Run
1. Clone the repository  
2. Install requirements:  
   ```bash
   pip install -r requirements.txt
