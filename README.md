# HOUSE_PRICE_PREDICTION_MODEL
# 🏠 House Price Prediction using Linear Regression

This project predicts California house prices using features like median income, average rooms, and location. The model is trained using Linear Regression, evaluated with RMSE, MAE, and R², and visualized using Seaborn and Matplotlib.

---

## 📌 Overview

This is a simple yet slightly advanced Machine Learning regression project where we:

- Load and preprocess the California Housing Dataset
- Train a Linear Regression model
- Evaluate the model using metrics like RMSE, MAE, and R² score
- Visualize predicted vs actual house prices
- Analyze feature importance based on model coefficients

---

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook (Anaconda)**
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## 📊 Dataset

- **Source:** `fetch_california_housing()` from `sklearn.datasets`
- **Target Variable:** `MedHouseVal` (Median house value)
- **Features include:**
  - Median income
  - Average rooms
  - Population
  - Latitude & Longitude
  - and more...

---

## 📈 Evaluation Metrics

| Metric | Value (Example Output) |
|--------|------------------------|
| RMSE   | ~0.72                  |
| MAE    | ~0.52                  |
| R²     | ~0.61                  |

> Lower RMSE and MAE = Better model  
> R² closer to 1 = Higher accuracy

---

## 📊 Visualizations

- 📉 Scatter plot: Actual vs Predicted prices
- 🔎 Feature Importance: Coefficients of each feature

---

## 🧪 How to Run

1. Install Anaconda or Jupyter Notebook
2. Clone the repo or upload the `.ipynb` notebook
3. Install required libraries:

```bash
pip install -r requirements.txt
