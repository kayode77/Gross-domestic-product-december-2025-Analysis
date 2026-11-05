
The dataset is a quarterly panel containing several GDP classifications and series. Initial EDA found no missing values or exact duplicates, but revealed large differences in scale between levels, a highly right-skewed Amount distribution, potential outliers and a strong positive association between Weight and Amount.

For the reported general regression experiment, Random Forest was the strongest model among Linear Regression, Lasso and Random Forest. It is the leading candidate from that comparison, but it has not thereby been validated as a future GDP forecasting model.

My next assignment is a dedicated forecasting experiment on one consistent series, such as Total GDP, with chronological evaluation and rolling-origin backtesting. Compare Random Forest, ETS, SARIMA and simple baselines before selecting a forecasting model.




