# OIBSIP Task 2: Unemployment Analysis with Python

## 📌 Project Overview
This project is part of the Oasis Infobyte Internship (OIBSIP). The objective of this task is to perform Exploratory Data Analysis (EDA) on unemployment data to uncover regional and temporal trends, with a specific focus on analyzing how the COVID-19 pandemic impacted the unemployment rate in India.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** 
  * `pandas` (Data loading, cleaning, and manipulation)
  * `matplotlib` & `seaborn` (Data visualization)

## 📊 Dataset
The dataset used in this project is the **"Unemployment in India"** dataset, sourced from Kaggle. It contains historical data on estimated unemployment rates, employment numbers, and labor participation rates across various regions (states) in India.

## 🚀 Project Workflow
1. **Data Loading & Cleaning:** Loaded the CSV file into a Pandas DataFrame. Cleaned column names, handled missing values, and converted the 'Date' column to a proper datetime format.
2. **Exploratory Data Analysis (EDA):** Calculated regional average unemployment rates and observed monthly trends.
3. **Time-Series Analysis:** Created a line chart to visualize the fluctuation of unemployment rates over time for three major states (Delhi, Maharashtra, Uttar Pradesh), highlighting the massive spike during the 2020 lockdown.
4. **State-Level Comparison:** Generated a bar chart showcasing the Top 10 states with the highest average unemployment rates during the recorded period.
5. **Correlation Heatmap:** Plotted a heatmap to understand the correlation between the Unemployment Rate, Estimated Employed workforce, and Labour Participation Rate.
6. **COVID-19 Impact Analysis:** Split the dataset into Pre-COVID (before April 2020) and During/Post-COVID periods to calculate and compare the mean unemployment rates, demonstrating the severe economic impact of the pandemic.

## 🏆 Key Observations
* There was a sharp and sudden increase in the unemployment rate starting in April 2020, directly corresponding to the nationwide COVID-19 lockdown.
* A strong negative correlation exists between the Unemployment Rate and the Estimated Employed workforce.
* States like Tripura and Haryana faced consistently higher average unemployment rates compared to the national average.

## 💻 How to Run This Project
1. Clone this repository to your local machine.
2. Navigate to the `OIBSIP/[TrackName]-Task2-UnemploymentAnalysis/` directory.
3. Ensure the `Unemployment_in_India.csv` file is in the same directory as the notebook.
4. Open the `Unemployment_Analysis.ipynb` file using Jupyter Notebook or Jupyter Lab.
5. Run the cells sequentially to observe the data cleaning process and generated visualizations.

---
**Author:** Junaed Ahamed  
**Internship:** Oasis Infobyte (OIBSIP)