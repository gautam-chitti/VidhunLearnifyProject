# Machine Predictive Maintenance Classification
![Python](https://img.shields.io/badge/python-3.11-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-0.87.0-blueviolet.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-brightgreen.svg)
![Joblib](https://img.shields.io/badge/Joblib-1.1.1-yellow.svg)


### Kaggle Dataset
(https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

## Dataset Description

The dataset consists of the following features:
- `UID`: Unique identifier ranging from 1 to 10000.
- `productID`: Product quality variant with letters L, M, or H, and a variant-specific serial number.
- `air temperature [K]`: Generated using a random walk process, later normalized to a standard deviation of 2 K around 300 K.
- `process temperature [K]`: Generated using a random walk process, normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.
- `rotational speed [rpm]`: Calculated from power of 2860 W, overlaid with normally distributed noise.
- `torque [Nm]`: Torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.
- `tool wear [min]`: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process.
- `machine failure`: A label that indicates whether the machine has failed in this particular data point for any of the following failure modes.