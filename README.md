#  Predictive Analysis of India’s Greenhouse Gas Emissions

This project uses machine learning models (Dense Neural Network and LSTM) to forecast sector-wise greenhouse gas (GHG) emissions in India up to 2050. The focus is on helping policymakers identify trends and prioritize climate action in sectors like energy, agriculture, and industry.

##  Key Features

- Sector-wise forecasting (Energy, Agriculture, Industry)
- Gas-specific predictions (CO₂, CH₄, N₂O)
- Models used: Dense Neural Network (DNN) and LSTM
- Forecast horizon: 2022 to 2050
- Model performance metrics: MAE, RMSE
- Data visualization and trend analysis

##  Machine Learning Models

- **Dense Neural Network (DNN)**: Captures nonlinear relationships in static emission data.
- **LSTM**: Time-series model for sequential trend learning.

##  Project Structure

- `notebooks/`: Jupyter notebook with code implementation.
- `data/`: Cleaned historical datasets used for training and testing.
- `report/`: Final project report and research paper.
- `requirements.txt`: Python dependencies.

##  Data Sources

- [Climate Watch (WRI)](https://www.climatewatchdata.org)
- [EDGAR (EU)](https://edgar.jrc.ec.europa.eu)
