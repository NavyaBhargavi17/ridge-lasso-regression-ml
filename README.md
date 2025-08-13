# Ridge and Lasso Regression - Machine Learning Implementation

## 📌 Overview
This repository contains **step-by-step Google Colab notebooks** for understanding and implementing **Ridge Regression** and **Lasso Regression** in Python using `scikit-learn`.

Both algorithms are used to address **overfitting** in linear regression by applying **regularization** techniques.

---

## 📖 Theory

### 1️⃣ Ridge Regression (L2 Regularization)
- **Formula:**
  $$
  \text{Cost Function} = \text{RSS} + \alpha \sum_{j=1}^{n} \beta_j^2
  $$
- **Key Point:** Adds the square of coefficients to the loss function.
- **Effect:** Shrinks coefficients towards zero but does not make them exactly zero.

---

### 2️⃣ Lasso Regression (L1 Regularization)
- **Formula:**
  $$
  \text{Cost Function} = \text{RSS} + \alpha \sum_{j=1}^{n} |\beta_j|
  $$
- **Key Point:** Adds the absolute value of coefficients to the loss function.
- **Effect:** Can shrink some coefficients to **exactly zero** → helps in feature selection.

---

## 🧠 Concepts Covered
- Regularization (L1 & L2 penalties)
- Multicollinearity handling
- Bias-Variance trade-off
- Model evaluation (MAE, MSE, RMSE, R²)

---

## 📂 Files in this Repository
- `Ridge_Regression.ipynb` → Google Colab notebook with Ridge Regression
- `Lasso_Regression.ipynb` → Google Colab notebook with Lasso Regression

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ridge-lasso-regression-ml.git
