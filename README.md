# 📈 Tesla Stock Price Prediction using ARIMA

This project demonstrates how to forecast Tesla's stock prices using the ARIMA (AutoRegressive Integrated Moving Average) time series model. The notebook includes data preprocessing, model training, forecasting, and evaluation.

---

## 📚 Project Structure

- Data Loading & Preprocessing  
  Load Tesla stock data and prepare it for ARIMA modeling (date parsing, indexing, cleaning).

- Model Building  
  Fit an ARIMA model using historical price data.

- Forecasting  
  Predict future Tesla stock prices using the trained ARIMA model.

- Evaluation  
  Compare predicted prices against actual values using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)

- Visualization  
  Plot historical data and forecasts for visual insight.

---

## 🔧 Technologies Used

- Python
- Pandas
- Statsmodels
- Matplotlib
- Scikit-learn (for metrics)

---

## 📁 Files

- Tesla_Stock_Price_Prediction.ipynb: Jupyter notebook with the full analysis.
- README.md: Project overview and instructions (you are here).
- Data avaliable in the "data" folder

---

## 📊 Example Forecast Plot

The notebook generates a plot showing historical Tesla stock prices and the ARIMA forecast.

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies:

```bash
pip install pandas matplotlib scikit-learn statsmodels
