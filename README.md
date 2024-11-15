# Time Series Analysis Project

## 1. Problem Statement
The goal of this project is to analyze time series data to uncover underlying patterns, such as trends and seasonality, and to make accurate predictions for future values. This project demonstrates how to approach forecasting tasks, which are essential in fields like finance, sales, and resource planning.

## 2. Data Sources
- **Dataset**: The time series data used in this project comes from [[Kaggle]](https://www.kaggle.com/competitions/demand-forecasting-kernels-only/overview).
- **Data Structure**: The dataset contains 913000 records with variables representing stores, their sales, item being sold.
- **Data Challenges**: Issues like missing values and potential anomalies were addressed during preprocessing to ensure the data’s reliability for modeling.

## 3. Approach to Solution
- **Methodology**: The project follows a structured approach, starting with exploratory data analysis (EDA) to identify patterns, followed by model selection, training, and evaluation.
- **Tools and Libraries**: Key tools include Python with libraries such as Pandas for data handling, Matplotlib/Seaborn for visualization, and statsmodels or pmdarima for time series modeling.
- **Models Used**: Time series models such as ARIMA and SARIMA were applied to capture trends, seasonality, and cyclic behaviors in the data.

## 4. Results and Conclusions
- **Results**: The final model achieved accurate predictions, demonstrating its suitability for forecasting tasks.
- **Insights**: Analysis revealed 
For each store and each item, a separate Prophet model can be used to improve forecast accuracy.
If selecting a single model, the choice would be XGBoost or LGBM.

- **Conclusion**: This project successfully showcases time series forecasting methods, highlighting their application for business forecasting and strategic decision-making. Future improvements could involve experimenting with advanced methods like LSTM networks or incorporating exogenous variables to improve accuracy.

The results:
![{97DFED25-86E9-4AC1-9784-ACB4FD66B7AC}](https://github.com/user-attachments/assets/a6f69667-3ff1-4f68-9daa-b6930be25fc4)
