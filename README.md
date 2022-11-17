## Project Overview
This project builds a time series model that forecasts monthly industrial production of electric and gas utilities in USA. The production is from all relevant establishments located in the United States, regardless of their ownership, but not those located in U.S. territories. The production outputs are measured and reported as industrial production (IP) index. Data was obtained from [ALFRED's economic data archive](https://fred.stlouisfed.org/series/IPG2211A2N), a US based economic research division and consisted of monthly industrial production index of the utilities from January 1939 to September 2022. The dataset used for this project and code script files can be found [here](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities)
## Objectives
This project aims at building a time series model that can forecast industrial production of electric and gas utilities for up to 36 months (3 years). To determine the best suited approach to build the model, we evaluate the data against various statistical and machine learning (ML) time series approaches and compare their models' forecasting performances to identify the one with the best performance. The statistical approaches evaluated are SARIMA and Prophet while those of ML are based on deep learning (i.e LSTM and 1 dimensional CNN).
## Task Performed
To accomplish the objective of the project, the following tasks were performed:
- Data profiling and time series conversion
- Handling of missing values
- Exploration data analysis
- Stationarity, autocorrelation and seasonality analysis
- Model evaluation
- Hyperparameter tuning
- Visualization of the model's performance
## Key Software and Libraries Used
* Python
* Scikit-learn
* Numpy
* Pandas
* Matplotlib
* Statsmodels
* Forecasting methods compared: SARIMA, Prophet, LSTM and 1D CNN
## Forecasting Result Summary
SARIMA was observed to outperform other models by achieving the lowest prediction errors with MAPE of 2.44 %, MAE of 2.479 and RMSE of 3.079.

![Original data presentation](Images/Production%20Output%201939%20-%202022.png)
![Visual of SARIMA forecasting performance](Images/SARIMA%20performance.png)
![SARIMA forecasting of 3 year production of utilities](Images/SARIMA%203%20year%20prediction.png)
![Visual of Prophet forecasting performance](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities/blob/main/Images/Prophet%20performance.png)
![Visual of LSTM forecasting performance](Images/LSTM%20performance.png)
![Visual of 1D CNN forecasting performance](Images/1D%20CNN%20performance.png)


