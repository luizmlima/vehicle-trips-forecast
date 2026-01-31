# Vehicle Trips Forecast - Transportation Demand Forecasting

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D1GbAcFUoKX_zlqxpsWBzHcYZfruL3Zt?usp=sharing)

## Description

This project implements and compares multiple **time series forecasting** models to estimate the volume of vehicle trips in Melbourne, Australia. It uses the **Vehicle Trips** dataset from the Monash repository, comparing classic statistical models with **Deep Learning** models (N-BEATS) for transportation demand forecasting.

## 📈 Results and Demonstration

The benchmark compared four main approaches. The **Theta** model showed the best overall accuracy, closely followed by the **N-BEATS** Deep Learning model.

### Final Precision Ranking

| Model | MSE | RMSE |
| :--- | :---: | :---: |
| **Theta (Best)** | **5342.32** | **73.09** |
| **N-BEATS** | 5979.14 | 77.32 |
| **Auto-ARIMA** | 21201.01 | 145.60 |
| **Naive (Baseline)** | 49565.40 | 222.63 |

### Visualization of Forecasts
Below, the graph shows the 243-month history and the performance of the models in the test period.



---

## Context

Transportation demand forecasting is essential for urban planning and infrastructure optimization. This project was developed as part of the **MEISSA** training program (LIAD/HP), exploring modern forecasting techniques.

## Technologies Used

- **Python 3.x**
- **Darts** - Specialized time series library
- **N-BEATS** - Deep Learning model for time series
- **Statsforecast & Prophet** - Statistical models
- **Pandas & Matplotlib**

## Methodology

1. **Dataset**: Vehicle Trips Dataset (Melbourne, Australia).
2. **Models**: Comparison between Naive Seasonal, Auto-ARIMA, Theta, and N-BEATS.
3. **Evaluation**: MSE and RMSE over a 12-month forecast horizon.

## How to Run

Click the "Open in Colab" badge at the top of this README to run the notebook directly in your browser.

## Author

**Luiz Anselmo Medeiros Lima**
- GitHub: [@luizmlima](https://github.com/luizmlima)
- LinkedIn: [Luiz Anselmo Lima](https://www.linkedin.com/in/luiz-anselmo-lima)

## MEISSA Project

This project was developed as part of the **MEISSA** training program, a partnership between the **Laboratório de Inteligência Artificial e Arquiteturas Dedicadas (LIAD)** and **HP**.
