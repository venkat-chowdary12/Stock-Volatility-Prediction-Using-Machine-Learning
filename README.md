# 📊 Stock Volatility Prediction using Machine Learning  
### Integrating Market and Macroeconomic Indicators  

## 📌 Project Overview  
This project focuses on predicting stock price volatility using machine learning models by combining market-derived features with macroeconomic indicators.  

Stock volatility is a key measure of risk and uncertainty in financial markets. Accurate prediction helps investors, analysts, and financial institutions make better decisions and manage risk effectively.  

---

## 🎯 Aim of the Project  
To evaluate the effectiveness of machine learning models in predicting stock price volatility and identify the best-performing model based on predictive accuracy.  

---

##  Research Questions  
- Can machine learning models accurately predict stock price volatility?  
- Does adding macroeconomic indicators improve model performance?  
- Which model performs best for volatility forecasting?  

---

## 📚 Dataset  
- Stock Market Data: MarketWatch  
- Macroeconomic Data: FRED (Federal Reserve Economic Data)  

### 🔹 Features Used  
- Market Features: OHLCV (Open, High, Low, Close, Volume)  
- Engineered Features:  
  - Log returns  
  - Rolling volatility (5, 21, 63 days)  
  - Moving averages  
  - Momentum indicators  
- Macroeconomic Features:  
  - Interest rates  
  - CPI (Inflation)  
  - Unemployment rate  
  - Treasury yield  

---

## ⚙️ Data Preprocessing  
- Data cleaning and handling missing values  
- Feature engineering and transformation  
- Alignment of time-series data  
- Feature scaling (for linear models)  
- Train-test split for model evaluation  

---

## 📊 Exploratory Data Analysis (EDA)  
- Analysed trends and volatility patterns over time  
- Examined feature distributions and relationships  
- Correlation analysis between variables  
- Identified key predictors influencing volatility  

---

## 🤖 Models Used  
- Ridge Regression (Linear Model)  
- Random Forest (Ensemble Model)  
- Gradient Boosting (Ensemble Model)  
- ARIMA (Time-Series Model)  
- SARIMAX (Time-Series Model with exogenous variables)  

---

## 📏 Evaluation Metrics  
- MAE (Mean Absolute Error) – measures average prediction error  
- RMSE (Root Mean Squared Error) – penalises large errors  
- R² Score – explains how well the model fits the data  

---

## 📈 Model Performance  

| Model              | RMSE    | MAE     | R² Score |
|--------------------|--------|--------|----------|
| Gradient Boosting  | 0.027  | 0.015  | 0.931    |
| SARIMAX            | 0.031  | 0.020  | 0.905    |
| Random Forest      | 0.034  | 0.017  | 0.890    |
| ARIMA              | 0.153  | 0.128  | -1.17    |

---

## 🏆 Key Results  
- Gradient Boosting achieved the best performance  
- Machine learning models outperformed traditional models  
- Nonlinear models captured complex market relationships effectively  
- Macroeconomic indicators improved prediction accuracy  

---

## 🚀 Future Work  
- Apply hyperparameter tuning (Grid Search / Random Search)  
- Implement deep learning models (LSTM, RNN)  
- Use rolling window / walk-forward validation  
- Add more macroeconomic indicators  
- Deploy model using cloud platforms (Azure ML)  

---
## ⭐ Conclusion  
This project demonstrates that machine learning combined with macroeconomic data can significantly improve stock volatility prediction, providing valuable insights for financial risk management and decision-making.  
