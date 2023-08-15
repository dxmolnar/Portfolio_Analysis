# A Whale off the Port(folio)

This project employs Python and Pandas to evaluate different investment portfolios, contrasting their risk and performance metrics.

### Files
The following source files can be found in the Portfolio_Analysis repo:
* aapl_historical.csv
* algo_returns.csv
* cost_historical.csv
* goog_historical
* sp500_history.csv

### Data Cleaning
Data from the csv files are read into Pandas DataFrame and cleaned by dropping null values.

### Perform Quantitative Analysis
Metrics for performance and risk are computed and illustrated for every portfolio. This encompasses daily returns, aggregate returns, box diagrams, evolving statistics, correlation assessments, and Sharpe ratios.

### Performance Analysis
Daily returns of all portfolios calculated and plotted. 

![cumulative_returns_plot](https://github.com/dxmolnar/Portfolio_Analysis/assets/127795314/71da7edc-49cc-4aa2-82a1-cb0af43463ad)

### Risk Analysis
* Box plots created
* Standard Deviation for all portfolios
* Portfolio comparisons
* Annualized standard deviation calculation

![box_plots_fund_mngmt](https://github.com/dxmolnar/Portfolio_Analysis/assets/127795314/af91ae0e-ed53-4585-a2a7-44c34b24e0a3)

### Rolling Statistics
* Rolling standard deviation for all portfolios, using a 21-day window calculated and plotted
* Correlation between each stock to determine which portfolios mimic the S&P 500 calculate and plotted 
* 60-day rolling beta between a Custom portfolio and the S&P 500 calculated and plotted
  
![21_day_exp_weighted_avg](https://github.com/dxmolnar/Portfolio_Analysis/assets/127795314/04f1d8ab-05a2-472c-96c0-1d9a2e20d44a)

## Custom Portfolio
A Custom portfolio was created to compare to previous portfolios such as the S&P 500

![final_pf_comparison](https://github.com/dxmolnar/Portfolio_Analysis/assets/127795314/5d6a0887-dbc8-49a9-ac49-9f23c03b8d04)

Final Result: 
Unfortunately the "Custom" portfolio didn't meet expectations. 
It not only lagged behind the S&P500 combined portfolio but essentially ended up being the second worse portfolio in the above shown list. 

The project, however, was an excellent way to show comparisons of various stock market portfolios. 

## Note
> Collaborated in part with Minh An Le. Some codes are therefore similar. 
