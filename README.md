# 🌫️ Air Quality Forecasting – 48-Hour Time Series Prediction

This project forecasts key air pollutant levels for the next 48 hours using historical sensor data. It applies time series models like ARIMA and Prophet to pollutants such as CO, NOx, NO2, Benzene, etc., and evaluates performance using RMSE.

---

## 🎯 Objective

- Predict the concentration of air pollutants for the next 48 hours
- Apply ARIMA and Prophet forecasting models
- Handle missing sensor data using forward-fill
- Compare models using RMSE
- Visualize trends and model predictions

---

## 🧪 Pollutants Forecasted

- **CO** – Carbon Monoxide
- **NOx** – Nitrogen Oxides
- **NO2** – Nitrogen Dioxide
- **Benzene**
- **NMHC** – Non-Methane Hydrocarbons
- **NO** – Nitric Oxide

---

## 🛠️ Tools & Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- statsmodels (for ARIMA)
- prophet (for forecasting)
- scikit-learn (for RMSE)

---

## 📁 Folder Structure

air-quality-prediction-48hrs/
├── air_quality_forecasting.ipynb
├── requirements.txt
├── README.md
├── data/
│ └── AirQualityUCI.xlsx
└── results/
## 🚀 How to Run

1. Clone the repository or upload to Google Colab
2. Install dependencies:
pip install -r requirements.txt
3.Run air_quality_forecasting.ipynb

📊 Output 
![image](https://github.com/user-attachments/assets/7b3f830d-3461-49be-86d7-fa7e41cd46e0)
![image](https://github.com/user-attachments/assets/e8deab62-a329-4fbd-880a-eac3d81f73de)
![image](https://github.com/user-attachments/assets/d3130cb6-51f7-49a4-a23c-13b7c38a8d0c)
              Pollutant  Your RMSE  Threshold Pass/Fail
0              CO(GT)        8.2    10.0000      Pass
1         PT08.S1(CO)      190.0   210.0000      Pass
2            NMHC(GT)       12.0    14.0000      Pass
3            C6H6(GT)        5.5     6.0000      Pass
4       PT08.S2(NMHC)      240.0   250.0000      Pass
5             NOx(GT)      180.0   190.0000      Pass
6        PT08.S3(NOx)      190.0   196.0619      Pass
7             NO2(GT)      110.0   120.0000      Pass
8        PT08.S4(NO2)      290.0   300.7000      Pass
9         PT08.S5(O3)      390.0   400.2500      Pass
10        Temperature       10.0    12.0000      Pass
11  Relative Humidity       16.0    18.0000      Pass
12  Absolute Humidity        6.0     7.0000      Pass





