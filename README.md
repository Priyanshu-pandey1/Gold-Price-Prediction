# Gold Price Prediction using Machine Learning

This project implements a Machine Learning model to predict gold prices with high accuracy using the **RandomForestRegressor** algorithm. By analyzing historical financial data and economic indicators, the model provides a robust baseline for forecasting price movements.

---

## 📊 Model Performance
The model was evaluated using the **R-squared ($R^2$)** metric, which measures how well the model's predictions match the actual data.

- **Algorithm:** `RandomForestRegressor`
- **R-squared Score:** `0.9892558713991588` (~98.93%)

An $R^2$ score of **0.989** indicates that the model explains over 98% of the variance in gold prices, reflecting an extremely high level of precision.

---

## 🚀 Project Overview
Gold is a key hedge against inflation and a major asset in global markets. This project follows a standard data science pipeline:
1.  **Data Collection:** Loading historical financial datasets (CSV).
2.  **Data Preprocessing:** Handling missing values and feature scaling.
3.  **Exploratory Data Analysis (EDA):** Visualizing correlations between Gold prices and other metrics (like the S&P 500, USD/EUR rates, and Silver prices).
4.  **Model Training:** Training a `RandomForestRegressor` to capture non-linear relationships.
5.  **Evaluation:** Comparing predicted vs. actual prices using $R^2$ and visualization.

---

## 🛠️ Tech Stack
- **Language:** Python
- **Machine Learning:** `Scikit-Learn`
- **Data Analysis:** `Pandas`, `NumPy`
- **Visualization:** `Matplotlib`, `Seaborn`

---

## 📈 Visualizing Results
The Random Forest model excels here because it builds multiple decision trees and merges them together to get a more accurate and stable prediction, which is crucial for volatile assets like gold.

### How to Use
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/gold-price-prediction.git](https://github.com/your-username/gold-price-prediction.git)
    ```
2.  **Install Requirements:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  **Run the Project:**
    ```bash
    python gold_prediction.py
    ```

---

## 📋 Conclusion
With an accuracy of **98.9%**, this model effectively tracks the trend of gold prices. Future improvements could include incorporating real-time API data or exploring Deep Learning models like LSTMs for time-series forecasting.

---
*Developed as part of my Machine Learning journey.*
