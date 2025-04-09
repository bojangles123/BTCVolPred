# BTCVolPred
This repository contains a Python script that processes minute-level BTC trading data and forecasts hourly realized volatility using engineered features and an XGBoost model.

Place all input files into the data/ directory. Due to licensing, I'm not able to provide minute-level BTC trading data. However, this can be found in sources like cryptolake. 

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
