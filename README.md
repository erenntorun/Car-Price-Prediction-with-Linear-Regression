# 🚗 Car Price Prediction with Linear Regression

This project aims to predict the **selling price of used cars** using linear regression. The dataset is sourced from `Car Dekho` and contains features like car age, fuel type, seller type, transmission, kilometers driven, etc.

## 📂 Dataset

The dataset used is one of the following:
- `car data.csv`
- `car details v3.csv`
- `car details v4.csv`
- All datasets are CSV files with similar schema and can be swapped if needed.

## 🔧 Technologies Used

- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🧪 Features Used

- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner
- Age

> 🎯 Target variable: `Selling_Price`

Categorical features are label encoded:
- `Fuel_Type` → Petrol: 0, Diesel: 1, CNG: 2  
- `Seller_Type` → Dealer: 0, Individual: 1  
- `Transmission` → Manual: 0, Automatic: 1

## 🧠 Model

A **Linear Regression** model is trained using scikit-learn's `LinearRegression()` class.

> Optionally, `Lasso Regression` is also included in comments and can be used for regularization purposes.

## 📈 Evaluation

The model performance is evaluated using **R² score** on both training and test datasets.

Additionally, matplotlib is used to **visualize actual vs predicted prices**.

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/erenntorun/car-price-prediction-with-linear-regression.git

2. Navigate to the project directory:
   ```bash
   cd car-price-prediction-with-linear-regression

3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

4. Make sure your dataset (e.g., car data.csv) is in the correct path.
 
5. Run the script
   ```bash
   python Car_Price_Prediction.py


📌 Notes
Update the CSV path at the beginning of the script if needed.

You can switch between different datasets by modifying the file path.

Ensure column names are consistent across datasets.



Created by @eren 👨‍💻
