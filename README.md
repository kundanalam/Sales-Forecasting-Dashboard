📊 Sales Forecasting Dashboard

A machine learning-based Sales Forecasting Dashboard built using Python, Streamlit, and Prophet.

The project analyzes historical sales data from the Superstore dataset and forecasts future sales based on historical patterns and seasonality.

🚀 Features

- Upload sales data through a CSV file
- Analyze historical daily sales
- Forecast future sales
- Compare actual sales with predicted sales
- Evaluate the model using MAE and RMSE
- Interactive Plotly visualizations
- View forecasted values in a table

🔄 How It Works

Sales Data
    ↓
Data Preprocessing
    ↓
Daily Sales Aggregation
    ↓
Prophet Time-Series Model
    ↓
Future Sales Forecast
    ↓
MAE & RMSE Evaluation
    ↓
Interactive Dashboard

🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Prophet
- Plotly
- Scikit-learn

📁 Project Files

- "app.py" — Streamlit dashboard and forecasting logic
- "Sample - Superstore.csv" — Sample sales dataset
- "requirements.txt" — Required Python libraries

🌐 Live Demo

👉 "Open Sales Forecasting Dashboard" (https://kundana-sales-forecast.streamlit.app/)

▶️ Run Locally

Install the required dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

🎯 Project Context

This project was developed as Task 1 of a Machine Learning Internship, focusing on applying time-series forecasting to a real-world retail sales dataset.
