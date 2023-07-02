## Project Overview
This project builds a univariate time series model that forecasts the monthly industrial production of electric and gas utilities in the USA. The production is from all relevant establishments located in the United States, regardless of their ownership, but not those located in U.S. territories. The production outputs are measured and reported as the industrial production (IP) index. Data was obtained from [ALFRED's economic data archive](https://fred.stlouisfed.org/series/IPG2211A2N), a US-based economic research division and consisted of monthly industrial production index of the utilities from January 1939 to September 2022. The dataset used for this project and code script files can be found [here](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities).
## Objectives
This project aims at building a time series model that can forecast industrial production of electric and gas utilities for up to 36 months (3 years). To determine the best-suited approach to build the model, we evaluate the data against two statistical time series approaches and compare their models' forecasting performances to identify the one with the best performance. The statistical approaches used for evaluation are SARIMA and Prophet.
## Task Performed
To accomplish the objective of the project, the following tasks were performed:
- Data profiling and time series conversion
- Analysis of missing values
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
* Pmdarima and Prophet libraries

## Time Series
Below is the graphical presentation of the time series analysed in this project.

![Original data presentation](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities/blob/main/Images/Time%20Series.png)

## Forecasting Result Summary
Below are the graphical presentations of the prediction performances of SARIMA and Prophet. It can be seen that SARIMA has outperformed Prophet by achieving the lowest prediction errors with MAPE of 2.44 %, MAE of 2.479 and RMSE of 3.079.

![Visual of SARIMA forecasting performance](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities/blob/main/Images/SARIMA%20performance.png)  
![Visual of Prophet forecasting performance](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities/blob/main/Images/Prophet%20performance.png)

Below is the plot of 3-year predictions of the utility production by SARIMA.

![SARIMA forecasting of 3 year production of utilities](https://github.com/Popseli/Forecasting-Industrial-Production-of-Electric-and-Gas-Utilities/blob/main/Images/SARIMA%203%20year%20prediction.png)


