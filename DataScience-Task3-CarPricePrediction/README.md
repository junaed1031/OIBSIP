# OIBSIP Task 3: Car Price Prediction with Machine Learning

## 📌 Project Overview
This project is part of the Oasis Infobyte Internship (OIBSIP). The primary objective of this task is to build a machine learning regression model that accurately predicts the selling price of used cars based on key attributes such as car age, mileage, fuel type, transmission, selling price, and brand.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** 
  * `pandas` & `numpy` (Data cleaning and feature manipulation)
  * `matplotlib` & `seaborn` (Data visualization)
  * `scikit-learn` (Machine learning modeling, encoding, and evaluation metrics)

## 📊 Dataset
The dataset used in this project is the **"Vehicle dataset from cardekho"**, sourced from Kaggle. It contains historical records of used cars including attributes like original purchase price (`selling_price`), year of manufacture (`year`), distance driven (`km_driven`), fuel type, seller type, and transmission.

## 🚀 Project Workflow
1. **Data Cleaning & Preprocessing:** 
   * Stripped whitespaces and handled missing/null values.
   * Dropped duplicate entries to ensure data integrity.
   * Standardized categorical string values (e.g., fuel types, transmission types).
2. **Feature Engineering:**
   * Calculated **`car_age`** by subtracting the manufacture year from the current year.
   * Extracted the **`brand`** name from the composite car name feature.
3. **Exploratory Data Analysis (EDA):**
   * Plotted price distribution to observe right-skewness.
   * Visualized price variations across different fuel types using Boxplots.
   * Examined the relationship between car age and selling price using Scatter plots.
4. **Encoding & Correlation Analysis:**
   * Converted categorical variables (`fuel`, `selling_type`, `transmission`, `brand`) into numeric features using One-Hot Encoding (`pd.get_dummies`).
   * Generated a Correlation Heatmap to identify top numerical predictors for selling price.
5. **Model Training & Evaluation:**
   * Split the dataset into 80% training and 20% testing sets using `train_test_split`.
   * Trained two regression models: **Linear Regression** and **Random Forest Regressor**.
   * Evaluated performance using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² Score.
6. **Feature Importance Analysis:**
   * Visualized top features driving model predictions using Random Forest feature importances.

## 🏆 Model Performance & Results

| Model | MAE | RMSE | R² Score |
| :--- | :--- | :--- | :--- |
| **Linear Regression** | 185,413.76 | 380,273.35 | 0.5511 |
| **Random Forest Regressor** | 158,510.40 | 365,448.47 | 0.5854 |


**Declared Best Model:** **Random Forest Regressor**. It achieved a significantly higher R² score (0.5854) and lower error metrics, effectively capturing non-linear relationships in car pricing. Key driving features included `selling_price`, `car_age`, and `km_driven`.

## 💻 How to Run This Project
1. Clone this repository to your local system.
2. Navigate to the `OIBSIP/DataScience-Task3-CarPricePrediction/` directory.
3. Ensure the `car data.csv` dataset file is present in the working directory.
4. Launch `Car_Price_Prediction.ipynb` in Jupyter Notebook or Jupyter Lab.
5. Execute all cells sequentially to view data transformations, visualizations, and model evaluations.

---
**Author:** Junaed 
**Internship:** Oasis Infobyte (OIBSIP)