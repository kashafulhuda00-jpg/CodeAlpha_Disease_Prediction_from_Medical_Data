## 📈 Model Performance Evaluation & Comparison
The models were evaluated using a stratified 20% testing split (240 patients total: 21 healthy, 219 disease-present):

### 1. Logistic Regression (Optimal Model)
* **Overall Accuracy:** 99%
* **ROC-AUC Score:** 1.0000 (Flawless class separation)
* **Disease Recall:** 100% (Zero false negatives; caught all 219 true positive cases)
* **Healthy Precision:** 100% (Zero false alarms for healthy patients)

### 2. XGBoost Classifier
* **Overall Accuracy:** 98%
* **ROC-AUC Score:** 0.9920
* **Disease Recall:** 100% (Successfully caught all high-risk cases)
