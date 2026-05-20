# Stock Price Predictor

A Machine Learning based Stock Price Prediction system developed using Python, Pandas, and ARIMA forecasting techniques.

---

## Overview

This project predicts stock market prices using historical stock datasets and time-series forecasting models. The system performs:

- Data Cleaning
- Feature Engineering
- Moving Average Analysis
- Volatility Analysis
- Time-Series Forecasting
- Visualization of Stock Trends

The project uses Apple (AAPL) and Tesla (TSLA) stock datasets.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```bash
Stock-Price-Predictor/
│
├── src/
│   ├── data/
│   │   ├── raw/
│   │   └── processed/
│   │
│   ├── notebooks/
│   │   └── arima_baseline.ipynb
│   │
│   └── outputs/
│       ├── plots/
│       ├── metrics/
│       └── predictions/
│
├── data_cleaning.py
├── data_featuring.py
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Features

### Data Cleaning
- Handles missing values
- Removes inconsistencies
- Cleans raw stock datasets

### Feature Engineering
- Daily Returns
- Moving Averages
- Rolling Volatility
- RSI Indicators

### Forecasting
- ARIMA Model Implementation
- Future Price Prediction
- Trend Forecasting

### Visualization
- Stock Closing Price Graphs
- Moving Average Charts
- Prediction vs Actual Graphs

---

## Dataset

Datasets Used:
- Apple Stock Data (AAPL)
- Tesla Stock Data (TSLA)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Mousoom07/Stock-Price-Predictor.git
```

Move into the project folder:

```bash
cd Stock-Price-Predictor
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Run data cleaning:

```bash
python data_cleaning.py
```

Run feature engineering:

```bash
python data_featuring.py
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

---

## Results

The project successfully predicts stock market trends using ARIMA forecasting techniques and visualizes future stock price movement using graphs and statistical analysis.

---

## Future Improvements

- LSTM Deep Learning Model
- Real-time Stock API Integration
- Interactive Dashboard
- Multi-stock Prediction System
- Live Forecasting

---

## Author

Developed by Mousoom Sama
