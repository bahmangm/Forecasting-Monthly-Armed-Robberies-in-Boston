# 📈 Forecasting Monthly Armed Robberies in Boston

This project explores the time series forecasting of monthly **armed robbery incidents** in Boston using classical statistical modeling techniques. The objective is to analyze historical patterns and build a predictive model to forecast future occurrences, with potential applications in law enforcement strategy and urban planning.

---

## 📘 Project Background

This work follows the structured, hands-on approach presented in the book:

**_“Introduction to Time Series Forecasting with Python: How to Prepare Data and Develop Models to Predict the Future” by Jason Brownlee_**

The project applies core concepts from the book to real-world crime data, progressing through data preparation, visualization, model evaluation, and forecasting.

---

## 🛠️ Techniques & Tools Used

- **Data Preprocessing & Cleaning**
- **Time Series Decomposition**
- **Stationarity Checks (ADF Test)**
- **Differencing for Trend Removal**
- **Autocorrelation & Partial Autocorrelation Analysis**
- **ARIMA Model Development**
- **Model Diagnostics & Forecasting**
- **Error Evaluation (MAE, RMSE)**

**Libraries:**
- `pandas`
- `matplotlib`, `seaborn`
- `statsmodels`
- `scikit-learn`
- `numpy`

---

## 🔍 Key Features

- Visualizes long-term trends and seasonal patterns in armed robbery incidents
- Tests for stationarity and applies appropriate differencing
- Selects optimal ARIMA parameters using ACF/PACF plots
- Forecasts future crime counts and visualizes prediction intervals
- Evaluates model accuracy using robust error metrics

---

## 🧠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bahmangm/Forecasting-Monthly-Armed-Robberies-in-Boston.git
   cd forecast-boston-armed-robberies
   ```

2. Open the notebook in Jupyter:
   ```
   Forecasting_Monthly_Armed_Robberies_in_Boston.ipynb
   ```

3. Run each cell sequentially to see the analysis and forecasts.

---

## 📁 Dataset

- **Source:** [Data Set](https://raw.githubusercontent.com/jbrownlee/Datasets/refs/heads/master/monthly-robberies.csv) 
- **Focus:** Monthly frequency of **armed robbery** cases from a specified historical range.

---

## 📌 Why This Matters

Forecasting crime data enables proactive measures by public safety agencies. Accurate predictions of armed robbery trends can help improve:

- 📍 Resource allocation
- 🚔 Police patrol planning
- 🏙️ Community safety initiatives

---

## 📊 Sample Output

Plots generated include:

- Time series line charts
- Seasonal decomposition graphs
- ACF and PACF plots
- ARIMA model diagnostics
- Forecast visualizations with confidence intervals

---

## ✅ Status

✔️ Completed exploratory and predictive analysis  
🔄 Future improvements may include exploring SARIMA, machine learning models, or external factors like weather and events.

---

## 📚 Acknowledgment

This project structure is inspired by the techniques outlined in:

**Jason Brownlee** – *"Introduction to Time Series Forecasting with Python: How to Prepare Data and Develop Models to Predict the Future"*
