# 🌧️ Rainfall Forecasting in Sri Lanka using Prophet

This repository contains a complete workflow for forecasting rainfall in Sri Lanka using Facebook Prophet, a robust and intuitive time-series forecasting library. The project uses a comprehensive weather dataset covering 30 major Sri Lankan cities from 2010 to 2023.

## 📌 Project Overview

Weather forecasting—especially rainfall prediction—is essential in agriculture, disaster management, and climate research. This repository includes a Jupyter Notebook showing steps for forecasting using Prophet

## 📂 Dataset Description

The dataset (2010-01-01 to 2023-01-01) includes weather observations collected from Open-Meteo and SimpleMaps. It contains:

- Time (timestamp)
- Weather codes
- Temperature (min, max, mean)
- Apparent temperature
- Sunrise/Sunset times
- Shortwave radiation
- Precipitation (total rainfall)
- Precipitation hours
- Wind speed, gusts, and direction
- Evapotranspiration (ET0)
- Latitude, longitude, elevation
- City & country fields

Dataset - [Kaggle](https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset)

## 📘 What is Prophet?

Prophet is an open-source forecasting procedure developed by Facebook's Core Data Science team. It is ideal for:

- Strong seasonal time series
- Long-term patterns
- Missing data
- Outliers
- Trend shifts

Prophet is available in both Python and R, and is built on top of Stan.

## 🛠️ Technologies Used

- Python 3
- Prophet (fbprophet / prophet)
- Pandas
- Matplotlib
- Jupyter Notebook

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone git@github.com:RashmikaD2001/Rainfall-Forecast-by-Prophet.git
cd Rainfall-Forecast-by-Prophet
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open the Notebook

```bash
jupyter notebook forecasting_using_prophet.ipynb
```

## 📊 Workflow Summary

1. Load and inspect rainfall dataset
2. Prepare Prophet-compatible dataframe:
   - `ds` → timestamp
   - `y` → rainfall amount
3. Fit Prophet model
4. Generate future predictions
5. Evaluate forecast accuracy

## 📈 Example Forecast Plot

_(Insert or upload an image once available)_

```python
forecast.plot()
forecast.plot_components()
```

## 🗂️ Repository Structure

```
📦 your-repo-name
 ┣ 📜 forecasting_using_prophet.ipynb
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📂 data
     ┗ sri_lanka_weather.csv
      
```

## 🙌 Acknowledgements

- [Prophet](https://facebook.github.io/prophet/) by Facebook
- [Kaggle](https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset) from Kaggle

⭐ If you find this project useful, please consider giving it a star!
