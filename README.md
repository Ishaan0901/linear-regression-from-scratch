#  Linear Regression From Scratch

This project implements **Simple Linear Regression from scratch in Python** using the mathematical formulas for slope and intercept — without using sklearn for training.
The implementation is validated by comparing results with `sklearn.linear_model.LinearRegression`.

---

## 📌 Objective

To deeply understand how Linear Regression works internally instead of just using pre-built libraries.

---

## 📊 Mathematical Formulation

Slope (m):
m = Σ (x - x̄)(y - ȳ) / Σ (x - x̄)²

Intercept (b):
b = ȳ - m * x̄

Prediction:
y = mx + b

---

## 🛠 Implementation Details

- Custom regression class
- Manual slope & intercept calculation
- Custom prediction function
- Train-test split
- Validation using sklearn

---

## 🔍 Verification with sklearn

The model was compared against:
from sklearn.linear_model import LinearRegression
Results:

- Slope matched exactly
- Intercept matched exactly
- Predictions matched exactly

This confirms that the implementation is mathematically correct.

---

## 🎯 What I Learned

- How slope and intercept are derived mathematically
- How libraries abstract internal ML logic
- Importance of data shape (1D vs 2D arrays)
- Practical understanding of model validation

---

## 🚀 Next Steps

- Implement Linear Regression using Gradient Descent
- Add visualization (Actual vs Predicted)
- Extend to multiple linear regression

---

## 👨‍💻 Author

Ishaan  
Aspiring Machine Learning Engineer  
Learning in Public 🚀
