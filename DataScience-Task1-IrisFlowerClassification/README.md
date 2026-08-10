# OIBSIP Task 1: Iris Flower Classification

## Project Overview
This project is part of the Oasis Infobyte Internship (OIBSIP). The objective of this task is to train a machine learning classification model to accurately identify the species of an Iris flower (Setosa, Versicolor, or Virginica) based on its physical measurements (sepal length, sepal width, petal length, and petal width). 

## Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** 
  * `pandas` (Data manipulation)
  * `matplotlib` & `seaborn` (Data visualization)
  * `scikit-learn` (Machine Learning modeling and evaluation)

## Dataset
The dataset used in this project is the classic **Iris Dataset**. It is loaded directly from the `scikit-learn` library (`sklearn.datasets.load_iris`), so no external download is required. The dataset contains 150 samples, with 50 samples for each of the three species.

## Project Workflow
1. **Data Loading:** Extracted the built-in dataset and converted it into a Pandas DataFrame for easier manipulation.
2. **Exploratory Data Analysis (EDA):** Checked the shape, data types, null values, and descriptive statistics of the dataset.
3. **Data Visualization:** 
   * Created a **Pairplot** to observe the distribution and relationships between features.
   * Generated **Boxplots** to check for outliers and feature spread across different species.
4. **Feature Selection:** Identified that `petal length` and `petal width` are the most discriminative features for classifying the species.
5. **Data Splitting:** Divided the dataset into training (80%) and testing (20%) sets using `train_test_split`.
6. **Model Training:** Trained two different machine learning algorithms:
   * Logistic Regression
   * Decision Tree Classifier
7. **Model Evaluation:** Evaluated both models using:
   * Accuracy Score
   * Confusion Matrix
   * Classification Report (Precision, Recall, F1-Score)
8. **Conclusion:** Selected the best-performing model based on the evaluation metrics.

## Results
Both models performed exceptionally well on this dataset. **Logistic Regression** was declared the best-performing model for this specific task due to its robustness and lower risk of overfitting on small, linearly separable datasets.

## How to Run This Project
1. Clone this repository to your local machine.
2. Navigate to the `OIBSIP/[TrackName]-Task1-IrisFlowerClassification/` directory.
3. Open the `Iris_Flower_Classification.ipynb` file using Jupyter Notebook or Jupyter Lab.
4. Run the cells sequentially to see the data analysis, visualizations, and model outputs.

---
**Author:** Junaed 
**Internship:** Oasis Infobyte (OIBSIP)