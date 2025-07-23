# House Price Prediction using Linear Regression


## 💡 Project Overview

This project focuses on building a **Linear Regression model** to predict the selling prices of houses based on key features such as:
- Living area in square feet (`GrLivArea`)
- Number of bedrooms (`BedroomAbvGr`)
- Number of bathrooms (`FullBath`)

The goal is to apply supervised learning techniques for real-world housing data and understand the relationship between features and target value (`SalePrice`).

---

## 📁 Dataset Description

The dataset used is from the [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

### Key Features:
- `GrLivArea`: Ground living area (in sq. ft.)
- `BedroomAbvGr`: Total number of bedrooms (above ground level)
- `FullBath`: Total number of full bathrooms
- `SalePrice`: The final price of the house (target)

---

## 🗃️ Files in This Repo

- `train.csv` – Training dataset with features and target.
- `test.csv` – Test dataset for predictions.
- `sample_submission.csv` – Format for submission file.
- `prodigy-ml-task1.ipynb` – Jupyter notebook with full code pipeline.
- `House_price_linear_regression_model.pkl` – Saved model (for future use).
- `README.md` – Project documentation.

---

## ⚙️ Requirements

Install the following Python libraries before running the notebook:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
