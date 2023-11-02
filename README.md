# Time Series Forecasting - Wine-Sales
The data of 2 different types of wine sales in the 20th century is to be analysed. Both of these data are from the same company but of different wines. As an analyst in the ABC Estate Wines, you are tasked to analyse and forecast Wine Sales in the 20th century.

## Types of wines that is to be analysed are: 
1) Sparkling Wine
2) Rose Wine

## Steps of working:
Solving the following questions on each of these two data sets separately.

- Acquire the data and interpret it as a Time Series dataset. Create a visual representation of the data through plotting
- Conduct an in-depth Exploratory Data Analysis (EDA) to gain insights into the dataset. Additionally, perform a decomposition analysis to understand its components.
- Divide the dataset into two parts: a training set and a test set. Ensure that the test set begins in the year 1991.
- Construct various exponential smoothing models using the training data and evaluate their performance on the test data by calculating the Root Mean Squared Error (RMSE). Additionally, create alternative models such as regression, naive forecasting, simple averaging, and moving averages on the training data and assess their RMSE on the test data.
- Evaluate the stationarity of the dataset used for model building by conducting relevant statistical tests, specifying the null and alternative hypotheses. If the data is deemed non-stationary, implement appropriate transformations or differencing to achieve stationarity. Then, examine the modified data for stationarity and provide commentary.
- Develop an automated version of the ARIMA/SARIMA model, selecting model parameters based on the lowest Akaike Information Criteria (AIC) using the training data. Evaluate this model's performance by calculating RMSE on the test data.
- Create ARIMA/SARIMA models based on cut-off points derived from the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) analyses using the training data. Evaluate the performance of these models on the test data by calculating RMSE.
- Compile a table summarizing all the models built, including their respective parameters and RMSE values on the test data.
- Utilize the model-building exercise to determine the most optimal model(s) based on the entire dataset. Forecast sales for the next 12 months, incorporating appropriate confidence intervals or prediction bands.
- Provide insights and observations about the model's performance. Suggest recommended actions and measures that the company should consider for future sales based on the analysis.

## file
1) Time Series Forecasting Report 
2) Sparkling Wine jupyter notebook
3) Rose Wine jupyter notebook

## Skills & Tools Covered
- Exploratory Data Analysis for Time Series Data
- Exponential Smoothing Models
- ARIMA/SARIMA Models
- Moving Average Models
