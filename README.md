
# Time Series Forecasting of Traffic Volume Using Statistical and Deep Learning Models

## Overview

This project focuses on **forecasting daily traffic volume** using both **statistical models** and **deep learning models**. The analysis combines rigorous **time series analysis** with modern machine learning techniques to achieve accurate and reliable predictions.

The dataset contains traffic volume data from **1st November 2015 to 30th June 2017**, aggregated on a daily basis. The primary goal is to compare the performance of **DIFF, ARIMA, SARIMA** (statistical models) with **LSTM** (deep learning model).

---

## 📂 Project Structure

```
.
├── Book/                  # References, learning materials, and resources
├── Code/                  # Python scripts and notebooks for the models
├── Dataset/               # Raw and processed datasets
├── Report/                # Detailed project report 
├── Time Series Analysis/  # Model-specific analysis and visualizations
├── Final_Code.pdf         # Final version of the implemented code
```

---

## 🔍 Key Features

* **Exploratory Data Analysis (EDA):** Understanding trends, seasonality, and stationarity.
* **Preprocessing:** Scaling, handling missing values, and holiday feature engineering.
* **Statistical Models:** DIFF, ARIMA, SARIMA, SARIMAX for baseline forecasting.
* **Deep Learning Model:** RNN, LSTM, GRU for capturing complex temporal dependencies.
* **Performance Evaluation:** Comparing models using metrics such as MAE, RMSE, and MAPE.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * `pandas`, `numpy` – Data manipulation
  * `matplotlib`, `seaborn` – Data visualization
  * `statsmodels` – Statistical time series modeling
  * `scikit-learn` – Preprocessing and evaluation metrics
  * `tensorflow` – LSTM model implementation

---

## 📊 Methodology

1. **Data Collection & Preprocessing**
2. **Stationarity Check & Differencing**
3. **Model Fitting** – DIFF, ARIMA, SARIMA, LSTM
4. **Hyperparameter Tuning**
5. **Forecasting & Evaluation**
6. **Result Comparison & Insights**

---

## 📈 Results Summary

* **Statistical Models:** Performed well for short-term forecasting.
* **Deep Learning Model (LSTM):** Captured complex seasonality and trends better for long-term predictions.

---

## 📄 Reports & Documentation

A detailed explanation of methodology, experiments, and results can be found in:

* `Report/` folder
* `Final_Code.pdf` for the full implementation

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/rathodjay19/Time-Series-Forecasting-of-Traffic-Volume-Using-Statistical-and-Deep-Learning-Models.git
   ```
2. Navigate to the `Code/` folder.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the desired notebook/script.

---

