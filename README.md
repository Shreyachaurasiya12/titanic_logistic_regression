# 🚢 Titanic Survival Prediction with Logistic Regression

This project uses the Titanic dataset to build a **Logistic Regression** model that predicts the **survival probability** of passengers. The solution walks through **EDA, preprocessing, model building, evaluation**.

---

## 📁 Project Structure
---

## 🔍 Exploratory Data Analysis (EDA)

- Inspected column types, null values, and feature distributions.
- Visualizations: histograms, boxplots, pairplots to detect patterns.
- Explored correlations with survival outcome.

---

## 🧹 Data Preprocessing

- Missing value imputation for Age and Embarked.
- Encoded categorical variables (e.g., Sex, Embarked).
- Feature scaling where necessary.

---

## 🤖 Model Building

- Logistic Regression using **Scikit-Learn**.
- Trained on Titanic training dataset.

---

## 📊 Model Evaluation

- Evaluated on accuracy, precision, recall, F1-score, ROC-AUC.
- Visualized **ROC curve**.
- Interpreted model coefficients to understand feature importance.

---

## 🚀 Deployment (Optional)

The model can be deployed using **Streamlit**:
- Users input age, sex, class, etc.
- Model returns predicted survival chance.


## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Streamlit  

---
