# 🏠 House Price Prediction using Linear Regression | SCT_ML_Task01

This project was completed as **Task 1** under the **Machine Learning Internship** at **Skill Craft Technology**.  
The goal was to build a **Linear Regression model** to predict house prices based on important features like area, number of bathrooms, and balconies.

## 📌 Task Details

- 🔹 **Task Name:** House Price Prediction
- 🔹 **Task Code:** `SCT_ML_Task01`
- 🔹 **Internship Role:** Machine Learning Intern
- 🔹 **Organization:** Skill Craft Technology

## 🎯 Objective

Predict house prices using:
- ✅ Carpet Area (in sqft)
- ✅ Number of Bathrooms
- ✅ Number of Balconies

Target variable: **Price (in ₹)**  
We converted real-world textual prices like `"42 Lac"` and `"1.4 Cr"` into numeric format using feature engineering.

## 📁 Dataset

- **Source:** Kaggle  
- **File Used:** `house_prices.csv`  
- Real estate listings with detailed features including title, price, area, and more.

## 🧹 Data Cleaning Steps

- Converted `Amount(in rupees)` to numeric ₹ using custom logic for `"Lac"` and `"Cr"`
- Cleaned `Carpet Area` from `"500 sqft"` → `500.0`
- Converted `Bathroom` and `Balcony` columns to float
- Removed missing values to prepare final dataset for modeling


## ⚙️ Model

- **Algorithm:** Linear Regression (Supervised ML)
- **Library:** `scikit-learn`
- **Train/Test Split:** 80/20
- **Features Used:**  
  - `Carpet_cleaned`  
  - `Bathroom`  
  - `Balcony`
## 📊 Evaluation

| Metric | Value |
|--------|-------|
| 🔸 R² Score | `~0.65-0.85` (depending on cleaned data) |
| 🔸 MSE (Mean Squared Error) | Shown via code |

**Visualization:**  
A scatter plot comparing **Actual vs Predicted** house prices to visually inspect the model performance.


## 📈 Output Snapshot

```plaintext
Actual Price   Predicted Price
-------------  ----------------
4200000        4100000
9800000        10100000
14000000       13600000
