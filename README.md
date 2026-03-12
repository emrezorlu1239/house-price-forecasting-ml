# 🏠 House Prices: High-Precision Forecasting

This project focuses on predicting residential home prices with high accuracy using the Ames Housing Dataset. By leveraging advanced feature engineering and optimized gradient boosting algorithms, the model achieves a high level of predictive performance.

## 🚀 Project Highlights
* **Top Performance:** Achieved an **R² score of 92.79%**.
* **Model:** Optimized **XGBoost** Regressor.
* **Feature Engineering:** Developed custom interaction features like `Qual_x_Area` and aggregated features like `Total_Living_SF`.
* **Precision:** Reduced Mean Absolute Error (MAE) to approximately **$13,187**.

## 📊 Methodology
1. **Data Cleaning:** Identification and removal of geographical and size-related outliers.
2. **EDA:** In-depth analysis of correlations between house features and sale prices.
3. **Feature Engineering:** Transformation of categorical variables and creation of new metrics that capture the synergy between house quality and size.
4. **Hyperparameter Tuning:** Systematic search for optimal parameters using `RandomizedSearchCV`.

## 📈 Visualizing Results
The model shows strong consistency across different price segments, as seen in the Actual vs. Predicted plots. The errors (residuals) are normally distributed, confirming the model's reliability.



## 🛠️ Tools Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Platform:** Kaggle

---

## 👤 Author
**Emre Zorlu**
* **Kaggle:** [@emrezorlu1239](https://www.kaggle.com/emrezorlu1239)
* **Project Link:** [Kaggle Notebook](https://www.kaggle.com/code/emrezorlu1239/house-prices-high-precision-forecasting)

---
*Feel free to reach out for collaborations or questions!*
