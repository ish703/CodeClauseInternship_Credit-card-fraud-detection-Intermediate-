# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions from highly imbalanced financial data.

---

## 🧠 Project Overview

Credit card fraud is a significant financial problem worldwide. In this project, machine learning techniques are used to identify suspicious transactions from anonymized financial data. 

Key challenges tackled:
- Imbalanced class distribution (fraud vs. legit)
- Choosing models that prioritize recall (catching frauds)
- Using synthetic oversampling (SMOTE) for better training balance

---

## 📂 Dataset

The dataset is available on Kaggle:  
🔗 [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

**Features:**
- 284,807 transactions  
- 492 are fraudulent  
- PCA-transformed features (`V1` to `V28`)  
- `Amount`, `Time`, and `Class` (target)  

---

## 🛠️ Technologies Used

- Python 3  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `imbalanced-learn` (for SMOTE)

---

## 📈 Workflow

- Data Preprocessing & Cleaning  
- Exploratory Data Analysis (EDA)  
- Handling Class Imbalance using SMOTE  
- Train-Test Split  
- Model Training:
  - Logistic Regression
  - Random Forest Classifier  
- Evaluation Metrics:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix  

---

## 📊 Model Results

| Metric        | Logistic Regression | Random Forest |
|---------------|---------------------|---------------|
| Accuracy      | 98.xx%              | 99.xx%        |
| Recall (Fraud)| 0.xx                | 0.xx          |
| Precision     | 0.xx                | 0.xx          |
| F1-Score      | 0.xx                | 0.xx          |

_Random Forest performed better on fraud recall and F1-score, making it suitable for high-risk applications._

---

## 📸 Visual Output

<details>
<summary>Click to View</summary>

![Confusion Matrix](C:\Users\hp\Pictures\Screenshots)  
_Confusion Matrix of Random Forest Predictions_

</details>

---

## ✅ Key Learnings

- Importance of dealing with imbalanced data in real-world problems
- How recall is more important than accuracy in fraud detection
- SMOTE helps improve model generalization on minority class
- Ensemble methods like Random Forest handle complex decision boundaries better

---

## 👨‍💻 Author

**Ishwar Singh Sisodiya**  
Final Year Engineering Student | Data Science Enthusiast  
Email: sisodiyaishwarsingh923@gmail.com
LinkedIn: (http://www.linkedin.com/in/ishwarsinghsisodiya)

