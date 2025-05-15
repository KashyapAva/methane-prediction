# 🌽 Methane Flux Prediction in Maize Fields using RNN & LSTM

This project focuses on predicting methane (CH₄) emissions in maize fields using deep learning techniques. We apply Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models to capture the temporal dynamics of methane flux based on environmental factors.

## 📌 Project Overview

Methane is a potent greenhouse gas, and understanding its emission patterns in agricultural systems is vital for climate action. This project builds on earlier work using statistical and machine learning models, enhancing performance by applying deep learning approaches suited for sequential data.

## 🧪 Methods Used
- Time series data preparation and gap filling
- Feature engineering with lagged environmental predictors
- RNN and LSTM model training and tuning
- Performance evaluation using RMSE and time series plots

## 🌱 Key Environmental Predictors
- Soil Temperature
- Soil Water Content
- Air Temperature
- Canopy Temperature
- Net Radiation
- Relative Humidity
- Precipitation

## 🧠 Models Explored
- **RNN**: Basic recurrent architecture that learns short-term patterns in sequential data.
- **LSTM**: Enhanced RNN variant that overcomes the vanishing gradient problem and captures long-term dependencies.

## 🎯 Key Results
- LSTM outperformed traditional RNN and classical models (SARIMA, random forest) in forecasting methane flux.
- Lagged variables significantly improved temporal predictive accuracy.
- Final RMSE on test data: *[Insert RMSE here]*

## 🛠 Tools & Frameworks
- Python
- TensorFlow / Keras
- Pandas, NumPy, Scikit-learn
- Matplotlib & Seaborn

## 📁 Repository Structure
- `Project2.ipynb`: Main model notebook
- `Cleaning.Rmd`: Data Cleaning in R
- `proj2_data_clan.csv`: Environmental inputs
- `Report.pdf`: Final summary

## 👤 Author
- Kashyap Ava

---

*Conducted as part of independent research in collaboration with the Department of Crop Sciences, UIUC.*
