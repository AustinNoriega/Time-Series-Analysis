![Time_Series_Analysis -_Austin_Noriega](https://github.com/user-attachments/assets/3c1536a5-3df0-4284-9219-98fefce1c688)

# Overview
This project focuses on using Time Series Analysis to forecast sales for the next 5 years at a commercial vehicle dealership. Some of the main questions to gain from the analysis are: 
* How does the trend line of sales change in the forecast?
* What are the optimal time for sales?

## Data overview: 
The dataset provided entails a list of monthly sales at the dealership for 11 years, with the columns being: 
* **Month-Year:** Date of Data sourcing, the middle of the month
* **Number of Trucks Sold:** Number of all of the trucks sold during that month

  
## Methodology: 
In order to do the needed analytics, the following modules and vizualizations were done: 
#### Modules: 
- Pandas & Numpy
- Matplotlib & Seaborn
- Statsmodels
  
#### Analysis Done:
- Boxplots
- ARIMA
- ARMA
- SARIMA
- Exponential Smoothing
## Summary of results: 
After creating the models, they were evaluated by the Root Mean Square Error (RMSE). The results showed that: 
- The seasonal __Exponential Smoothing__ model preformed the best, with a total RMSE score of 44
- The sales are continuously rising, with the sales mostly being in the summer months
- Over the next 5 years, there will be a 36% increase in sales overall 

## Further Considerations ##
One of the main options for further research and consideration are:
- Additional reseach can be conducted to find out specifically what contributes to the higher sales in the months of May - August
  
