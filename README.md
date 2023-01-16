# Linear Regression Model for GDP Forecasting
This program utilizes historical data from the S&P 500, Consumer Price Index, and Federal Funds Rate to train a linear regression model to predict GDP values. The data is preprocessed to extract only the date and close prices for the S&P 500, and the date and value for the GDP, CPI, and FFR. The data is then cleaned by removing duplicates and any missing values, and scaled using Standard Scaler. The linear regression model is trained on the preprocessed data, and the coefficients of the model are extracted. The program then runs a Monte Carlo simulation for 1000 iterations to generate a range of predictions for the GDP. The mean and standard deviation of the predictions are calculated to give an idea of the uncertainty of the model's predictions.

Step by step guide to install relevant libraries:

Install numpy by running pip install numpy in the command line.
Install pandas by running pip install pandas in the command line.
Install sklearn by running pip install -U scikit-learn in the command line.
