# Prediction of Net Income and Price Volatility of Coffee in Mexico Using Machine Learning

**Author:** Arait Monter Corona

**Degree / Institution:** BSc in Applied Mathematics and Computer Science, Uiversidad Nacional Autónoma de México (UNAM) 
**Year:** 2024  

This repository hosts the final PDF of this research and its sources used to develop and validate the results.

---

## Abstract

This research analyzes the relationship between coffee price volatility and net income of coffee producers in Mexico, within the context of the TEEB AgriFood Mexico project. Using a multi-source dataset that combines producer-level information with economic, environmental, climatic, and social indicators, the study first characterizes historical price dynamics and volatility patterns (1990 - 2024) and then evaluates predictive approaches for both price variation and producer income. For price dynamics, annual coffee price indicators are modeled as normalized time series and forecasted using AutoARIMA, selected via information criteria (AIC), enabling a medium-term scenario analysis. For income prediction, a supervised learning pipeline is implemented with Z-score standardization and one-hot encoding of categorical variables (including a municipal volatility class: high/medium/low), and models are evaluated with an 80/20 train–test split. Four regressors are benchmarked: Multiple Linear Regression, Random Forest, Gradient Boosting, and XGBoost. Results show that XGBoost achieves the best performance (MAE = 25,400 MXN; RMSE = 49,700 MXN; R² = 0.75; MAPE = 14.1%) and supports a five-year net-income scenario (2025–2029). Feature-importance analysis highlights the relevance of ecological and structural factors—such as forest/jungle cover, municipal price volatility, yield, indigenous language, and participation in support programs (ProCafé)—suggesting that income outcomes reflect both market exposure and socio-environmental vulnerability. Overall, the thesis provides a data-driven framework to support scenario planning and targeted interventions for coffee-producing regions in Mexico.
