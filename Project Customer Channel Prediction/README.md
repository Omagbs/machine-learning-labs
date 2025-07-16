# Predicting Customer Purchase Channel: Mobile App vs Website

This project explores customer shopping behavior for an online clothing retailer. The company offers in-store personal stylist sessions after which customers place their orders either via the **mobile app** or the **website**.

The goal is to use **linear regression** to analyze which platform customers are more likely to use, based on the session details and other features in the dataset. This will help the company decide where to focus their digital efforts.

---

## 📊 Dataset Description

The dataset contains the following columns (example):
- `session_length`: Duration of the stylist session
- `time_on_app`: Time spent on the mobile app
- `time_on_website`: Time spent on the website
- `yearly_amount_spent`: Total yearly purchase amount
- `channel`: (optional target) whether they used **app** or **web** for final order

---

## 🔧 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🚀 Steps in the Notebook

1. Data loading and exploration
2. Data visualization
3. Correlation analysis
4. Train/test split
5. Linear regression model fitting
6. Evaluation (R², MSE)
7. Business insights & recommendations

---

## 📈 Key Insights

- Does time on app or website correlate more with yearly spending?
- Should the company focus more on the app or the website?
- Which variable is most predictive of purchasing behavior?

---

## 📁 Folder Structure
├── customer_data.csv
├── notebook.ipynb
├── README.md