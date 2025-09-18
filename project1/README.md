# Polynomial Regression: Optimizing Model Complexity

## 📌 Project Description

This project investigates **polynomial regression** as a method for
modeling nonlinear relationships between input and output data.\
The primary focus is on understanding how the degree of the polynomial
influences:

-   Model performance\
-   Generalization ability\
-   The trade-off between **underfitting** and **overfitting**

By experimenting with training, validation, and test datasets, the
notebook provides an applied framework for selecting the optimal
polynomial degree using **Root Mean Squared Error (RMSE)** and
visualization techniques.

------------------------------------------------------------------------

## 🗂 Contents

The Jupyter Notebook is organized into the following main sections:

### 1. Dataset Import

-   Uploads training, validation, and test sets.\
-   Converts data into NumPy arrays for efficient computation.

### 2. Linear Regression (Baseline)

-   Implements simple linear regression using closed-form equations.\
-   Provides an initial benchmark for performance comparison.

### 3. Data Visualization

-   Plots actual data points and regression fits.\
-   Uses color-coded graphs for training, validation, and test sets.

### 4. Polynomial Regression

-   Expands features up to polynomial degree 10.\
-   Fits regression models for each degree using the normal equation.

### 5. Evaluation Metrics

-   Computes RMSE for training, validation, and test sets.\
-   Compares errors across polynomial degrees.

### 6. Model Selection & Analysis

-   Identifies the optimal polynomial degree by analyzing error trends.\
-   Demonstrates how overfitting increases validation/test error.

------------------------------------------------------------------------

## ⚙️ Requirements

To run the notebook successfully, install the following dependencies:

``` bash
pip install numpy pandas matplotlib
```

------------------------------------------------------------------------

## 🚀 Usage Instructions

1.  Open the notebook in **Google Colab** or **Jupyter Notebook**.\
2.  Upload the following datasets when prompted:
    -   `Dataset_1_train.csv`\
    -   `Dataset_1_valid.csv`\
    -   `Dataset_1_test.csv`\
3.  Execute all cells in sequence.\
4.  Review:
    -   📈 Plots to visualize model fits\
    -   ✅ RMSE values to compare model accuracy

------------------------------------------------------------------------

## 📊 Results & Insights

-   Low-degree models (e.g., linear regression) often **underfit**,
    failing to capture data complexity.\
-   High-degree models may perfectly fit training data but **overfit**,
    leading to poor validation/test performance.\
-   The **optimal polynomial degree** minimizes validation RMSE while
    maintaining generalization to unseen data.

This illustrates the importance of the **bias-variance trade-off** in
machine learning.

------------------------------------------------------------------------

## 📁 Project File

-   **Aida_Chamani_Project1.ipynb** → Contains all implementations,
    visualizations, and analyses.

------------------------------------------------------------------------

## ✨ Key Learning Outcomes

-   How to apply **linear and polynomial regression** in Python.\
-   How to evaluate models using **RMSE**.\
-   How to select the right model complexity by balancing **underfitting
    vs. overfitting**.\
-   How to interpret results using both **visual** and **numerical**
    analysis.

------------------------------------------------------------------------
