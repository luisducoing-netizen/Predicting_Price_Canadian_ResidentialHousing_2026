# Predicting Canadian Residential Housing Prices 🏠🇨🇦

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest%20%26%20MLR-green.svg)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

## 📌 Project Overview
This predictive analytics project leverages Machine Learning to estimate residential property values across Canada. By analyzing a comprehensive dataset of **44,000+ listings**, the model identifies key pricing drivers and provides data-driven insights into the Canadian real estate market.

The project compares two main approaches: **Multiple Linear Regression (MLR)** and **Random Forest Regressor** to determine the most accurate method for valuation.

## 🚀 Key Results
*   **Model Accuracy:** Achieved a **71.79% R-squared score** using the Random Forest model.
*   **Data Scope:** Analysis of over 44,000 unique residential listings across various Canadian provinces.
*   **Feature Importance:** Identified that location, square footage, and property type are the most significant predictors of price.

## 🛠️ Tech Stack
*   **Programming Language:** Python
*   **Libraries:** 
    *   `Pandas` & `NumPy` for data manipulation.
    *   `Scikit-Learn` for model training and evaluation.
    *   `Matplotlib` & `Seaborn` for data visualization.
*   **Models Used:** 
    *   Random Forest Regressor
    *   Multiple Linear Regression (MLR)

## 📁 Repository Structure
*   📄 **[BUSI 651_Team_Project_Group2 FINAL.pdf](./BUSI%20651_Team_Project_Group2%20FINAL.pdf):** Full academic report containing executive summary, methodology, and detailed business conclusions.
*   🐍 **[Group_2_Final_Project_RandomForest.py](./Group_2_Final_Project_RandomForest.py):** Python script implementing the Random Forest model, including hyperparameter tuning.
*   🐍 **[Group_2_Final_Project_Regression.py](./Group_2_Final_Project_Regression.py):** Python script focused on the Multiple Linear Regression analysis and statistical testing.
*   📄 **README.md:** Project documentation.

## 📊 Methodology
1.  **Exploratory Data Analysis (EDA):** Visualizing price distributions and correlation matrices.
2.  **Data Preprocessing:** Handling missing values, encoding categorical variables (Province, City), and feature scaling.
3.  **Model Training:** Training both MLR and Random Forest models using an 80/20 train-test split.
4.  **Evaluation:** Comparing models using R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## ⚙️ How to Use
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/luisducoing-netizen/Predicting_Price_Canadian_ResidentialHousing_2026.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  **Run the analysis:**
    ```bash
    python Group_2_Final_Project_RandomForest.py
    ```

## 👥 Contributors 
This project was developed as part of the **BUSI 651** course by:
*   **Rasadokht Ostadagha** 
*   **Matheus Fontanella**
*   **Maria Rayane Chagas Yamamoto** 
*   **Luis Ducoing** 
*   **Fabio Sueto** 
---
⭐ *If you find this project useful, feel free to give it a star!*
