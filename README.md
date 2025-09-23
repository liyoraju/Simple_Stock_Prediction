# Stock Forecast App

This is a **Stock Forecasting Web App** built with **Streamlit**, **Prophet**, **yFinance**, and **Plotly**. It allows users to select a stock and predict its future prices for up to 5 years using historical data.

---

## Features

- Select a stock from predefined options: Google (GOOG), Apple (AAPL), Microsoft (MSFT), GameStop (GME), Tata Steel (TATASTEEL.NS).  
- View raw historical stock data.  
- Plot stock opening and closing prices with interactive Plotly charts.  
- Forecast future stock prices using **Facebook Prophet**.  
- Visualize forecast components such as trend, weekly, and yearly seasonality.  

---

## Installation

### 1. Clone this repository:

git clone your-repo-url

cd repo-folder

### Create a virtual environment (optional but recommended):

python -m venv venv

source venv/bin/activate   # Linux/Mac

venv\Scripts\activate      # Windows

### Install dependencies:
pip install -r requirements.txt

### Usage
Run the Streamlit app: streamlit run app.py

Select a stock from the dropdown menu.

Adjust the number of years for the forecast using the slider.

The app will display raw data, interactive plots, and forecasted prices.

### Dependencies
streamlit

yfinance

prophet

plotly

pandas

numpy


License
This project is licensed under the MIT License.

Author   
Liyo C Raju – Data Science & AI enthusiast
