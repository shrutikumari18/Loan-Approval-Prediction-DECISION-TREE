# 📊 Loan Approval Prediction using Decision Tree

## 📌 Overview

This project predicts whether a loan application will be approved or not using a Decision Tree Classifier. The model is trained on financial and asset-related features.

---

## 📂 Dataset

* Total Records: 4269
* No missing values
* Features include income, loan amount, credit score, assets, etc.

### 🎯 Target:

* loan_status (Approved / Rejected)

---

## ⚙️ Workflow

1. Data Loading
2. Column Cleaning (removed extra spaces)
3. Dropped unnecessary column (`loan_id`)
4. Label Encoding for categorical features
5. Train-Test Split (80-20)
6. Model Training (Decision Tree)
7. Evaluation (Accuracy + Confusion Matrix)
8. Visualization

---

## 🧠 Model Used

* Decision Tree Classifier
* Controlled overfitting using max_depth

---

## 📈 Results

* Achieved good accuracy
* Identified important features like CIBIL score and income
* Visualized decision tree

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## 📁 Project Structure

```
Loan-Approval-Prediction/
│
├── data.csv
├── main.py
├── README.md
├── requirements.txt
```

---

## 🔮 Future Improvements

* Use Random Forest
* Hyperparameter tuning
* Build web app using Streamlit

---

## 👩‍💻 Author

Shruti Kumari
B.Tech CSE (Data Science)

---
