# Solar-Forecast-with-Deep-Learning
Project Description
This project aims to develop energy consumption forecasting models by analyzing electricity usage data from the city of Tétouan, Morocco. The dataset used is the "Electric Power Consumption" dataset available on Kaggle.

Dataset and Preparation
The dataset is provided in CSV format and contains electricity consumption data for three distinct zones (Zone 1, Zone 2, Zone 3) of Tétouan, recorded every 10 minutes (6 samples per hour). Features include date-time, temperature, humidity, wind speed, general diffuse flows, and diffuse flows, with the target variables being the power consumption of each zone. During preprocessing, the dataset was cleaned, missing values were addressed, and it was optimized for analysis. Additionally, the data was manipulated to enable predictions for user-specified time horizons.

Developed Model and Analysis
An LSTM (Long Short-Term Memory) model was employed to predict electricity consumption. The model was trained on the dataset, enhanced with optimization algorithms, and achieved an R² score of up to 95.6%. Results were visualized through graphs, and comparisons with other models were conducted. Predictions were evaluated separately for each zone, supported by detailed analyses.

Objective and Contribution
This study seeks to improve energy planning and management by accurately forecasting city-level electricity consumption. The developed models, visualizations, and analyses are shared to provide guidance and inspiration to researchers and professionals in the energy sector.
DATASET= https://www.kaggle.com/code/nechbamohammed/electric-power-consumption-forecasting
