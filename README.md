# 📈 Time Series Forecasting for Beer Production

## 🚀 Project Purpose

This Time Series Forecasting project revolves around predicting future beer production based on historical data. It equips stakeholders in the beer industry with a powerful tool to make informed decisions, optimize resources, and plan effectively.

The primary goal is to provide accurate predictions, enabling businesses to anticipate fluctuations in production and make proactive adjustments to meet demand. By leveraging advanced time-series models like SARIMA (Seasonal Autoregressive Integrated Moving Average), the project captures underlying patterns and seasonality in beer production data. By looking at past production data, we can make smart decisions, manage resources better, and plan effectively. It's like having a crystal ball for beer production.
## 🔍 Problem Statement

Predicting beer production is crucial for breweries to ensure they make enough to meet demand without overproducing. This forecasting tool helps brewery stakeholders make informed decisions, optimize resources, and plan effectively to meet market demand.

## 📊 Key Aspects and Features

### 🔄 Time-Series Analysis:
We use advanced time-series models, like SARIMA, to understand patterns and seasonality in beer production data. It's like learning from the past to predict the future.

### 🌐 User-Friendly Streamlit App:
We've created a simple web app using Streamlit. You can interactively explore and visualize forecasted beer production by adjusting parameters like the start date and the number of forecast steps.

### 🤖 Automated Forecasting:
Our project automates the forecasting process, so you don't need to be a data science expert. Just input what you want to know, and we'll do the math to give you reliable predictions.

### 📊 Model Evaluation Metrics:
The app displays important model evaluation metrics like Mean Squared Error (MSE) and Root-Mean Squared Error (RMSE) to assess how accurate our predictions are.

### 📁 GitHub Repository:
All our code is organized neatly on GitHub. It's like an online file cabinet where anyone can see what we're doing, suggest changes, and stay updated on the latest developments.

## 🛠️ Technologies and Techniques Used

### 🐍 Python:
We've implemented the project in Python, a versatile and widely-used language in data science.

### 🐼 Pandas and NumPy:
Pandas helps us organize our data, and NumPy handles numerical operations for efficient data processing.

### 📊 Statsmodels:
Statsmodels is like our math guru, helping us analyze time-series data with models like SARIMA.

### 🚀 Streamlit:
Our user-friendly web app is built with Streamlit for easy interaction with the forecasting model.

### 📈 Matplotlib and Altair:
These are our visual artists, helping us create insightful graphs to represent historical and forecasted data.

### 🔄 GitHub Actions:
We use GitHub Actions for continuous integration, making sure our code is always in good shape.

## 📄 Usage
Clone the Repository:

```bash
git clone https://github.com/Bidishabiswas1704/Time_series_analysis
```

Install Dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit App:

```bash
streamlit run beer_forecasting_app.py
```

Open the web browser and go to http://localhost:8501 to explore the beer production forecasting application.

## 📊 Example Screenshots

### User Input

![image](https://github.com/Bidishabiswas1704/Time_series_analysis/assets/140384850/0e990f31-cce8-4a3e-8fb7-281014699593)

From Start date, we can pick the date of our choice with the help of calander provided in the tab, as shown below:

![image](https://github.com/Bidishabiswas1704/Time_series_analysis/assets/140384850/2283f342-d78c-4a60-bec6-07febb4f7cdb)

The number of forecasting steps can be filled with the help of (+) and (-) icons as shown below:

![image](https://github.com/Bidishabiswas1704/Time_series_analysis/assets/140384850/c9ae4b50-9744-40b8-bace-2e78fa40f8a8)


### Production Forecast Plot

![image](https://github.com/Bidishabiswas1704/Time_series_analysis/assets/140384850/e6bec98b-ba06-43af-b63f-920e67785598)


### Forecasted Production

![image](https://github.com/Bidishabiswas1704/Time_series_analysis/assets/140384850/fba62730-bd69-4253-a1e0-b0a12c8214fa)

## 📂 Directory Structure

```
.
├── data/
│   └── monthly-beer-production.csv
├── notebooks/
│   └── exploratory_analysis.ipynb
├── screenshots/
│   ├── screenshot1.png
│   └── screenshot2.png
├── beer_forecasting_app.py
├── sarima_model.pkl
├── requirements.txt
├── README.md
└── .github/
    └── workflows/
        └── ci_cd.yml
```

## 🤝 Contribution

Contributions are welcome! Feel free to open issues, propose new features, or submit pull requests.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
```

Feel free to customize it further based on your project details.
