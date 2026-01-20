# 🎬 Movie Revenue Prediction

This project analyzes a dataset of movie financials to determine if there is a strong correlation between a movie's **production budget** and its **box office revenue**. It utilizes **Linear Regression** to build a predictive model and evaluates its validity based on training and testing scores.

## 📄 Project Overview

The primary goal of this exercise is to load, clean, and analyze movie data to check for correlation links with the "Budget" feature. A linear model is then constructed to predict "Revenue".

## 🛠️ Workflow

The notebook follows these specific steps:
1.  **Data Loading**: Imports movie data (`revenue-1.csv`) using Pandas.
2.  **Data Cleaning**: Checks for null values to ensure data integrity.
3.  **Correlation Analysis**: Generates a correlation matrix to identify features strongly linked to "Budget".
4.  **Visualization**: Plots "Budget vs Revenue" to visualize the relationship (Correlation ~0.67).
5.  **Data Splitting**: Divides the dataset into 80% Training and 20% Testing sets.
6.  **Model Training**: Trains a **Linear Regression** model using Scikit-Learn.
7.  **Evaluation**: Scores the model on both training and test sets.
8.  **Visualization**: Plots predicted values against actual test data.
9.  **Decision Tree**: Briefly explores a Decision Tree model for comparison.

## 📊 Key Results

* **Correlation**: The data showed a correlation of approximately **0.67** between Budget and Revenue.
* **Model Performance**:
    * Training Score: ~0.97
    * Test Score: ~0.64
* **Conclusion**: Based on the evaluation criteria (expecting a score > 0.8), the linear model was determined to be **not valid** for this specific dataset due to insufficient predictive power on the test data.

## 🧰 Technologies Used

* **Python**
* **Pandas** (Data manipulation)
* **NumPy** (Numerical operations)
* **Matplotlib** (Data visualization)
* **Scikit-Learn** (Machine Learning models)

## 🚀 How to Run

1.  Clone this repository.
2.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy matplotlib scikit-learn
    ```
3.  Open the notebook `movie-revenue-prediction.ipynb` in Jupyter Notebook or Google Colab.
4.  Run the cells sequentially to reproduce the analysis.

---
*Created as part of a Data Science & AI exercise.*
