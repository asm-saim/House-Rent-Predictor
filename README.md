
# 🏡 House Rent Predictor

This project is a machine learning model that predicts house rent prices based on features like area, number of bedrooms, and bathrooms. It applies core regression techniques and model evaluation metrics to build and assess prediction accuracy.

---

## 🚀 Project Objectives

- Predict house rent prices using regression models
- Understand and apply concepts of:
  - Linear Regression
  - Overfitting and Regularization
  - Ridge (L2 penalty) and Lasso (L1 penalty) Regression
- Evaluate models using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score (Coefficient of Determination)

---

## 📚 Technologies & Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (sklearn)

---

## 📈 Models Trained

1. **Linear Regression**
2. **Ridge Regression** (`alpha=1.0`)
3. **Lasso Regression** (`alpha=1.0`)

Each model was evaluated and compared using standard regression metrics (MAE, RMSE, R² Score) to select the best-performing one.

---

## 📊 Model Evaluation

| Metric | Linear | Ridge | Lasso |
|--------|--------|-------|-------|
| MAE    | ✅ Calculated | ✅ Calculated | ✅ Calculated |
| RMSE   | ✅ Calculated | ✅ Calculated | ✅ Calculated |
| R²     | ✅ 0.63+ | ✅ 0.63+ | ✅ 0.63+ |

> The Ridge model gave the best balance of accuracy and generalization based on R² and error metrics.

---

## 📁 Dataset Columns

- **Location** (dropped)
- **Area** (converted to integer)
- **Bed** (number of bedrooms)
- **Bath** (number of bathrooms)
- **Price** (target value, in BDT)

---

## 🛠 How to Use

1. Upload the dataset (`.csv`) in Google Colab
2. Preprocess:
   - Clean Area and Price columns
   - Handle Location (drop)
3. Train the models using `sklearn`
4. Evaluate with `mean_absolute_error`, `mean_squared_error`, and `r2_score`

---

## 📎 Example Output

```
MAE: 6638.74
RMSE: 13002.34
R² Score: 0.6341
```

---

## 🤖 Future Work

- Improve predictions with more features like location encoding
- Use advanced models (e.g., Decision Trees, Random Forests)
- Deploy as a web app using Streamlit or Flask

---

## 📬 Contact

Created by asm-saim – feel free to connect!
