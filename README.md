# BTCVolPred
This repository contains a Python script that processes minute-level BTC trading data and forecasts hourly realized volatility using engineered features and an XGBoost model.

Place all input files into the data/ directory. Due to licensing, I'm not able to provide minute-level BTC trading data. However, this can be found from sources such as Cryptolake. 

Run the script:
python fundingdiagnosis.py

The script generates a chart comparing actual vs. predicted hourly BTC volatility:
data/actual_vs_predicted_volatility.png

Dependencies:
- pandas
- numpy
- xgboost
- matplotlib
- scipy
- scikit-learn

Of note: This script is not appropriate to use for vol prediction when trading options because of how this model calculates volatility. However, it can serve as a frame of reference of expected directional volatility. 
