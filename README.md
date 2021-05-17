# A Whale off the Port(folio)
---

This repository contains plementation of financial data analysis of stock prices using Pandas to evaluate the performance of various algorithmic, hedge fund, and mutual fund portfolios and compare their performance against the S&P 500 Index. 

Implementation also constructs a custom portfolio, compute weighted return of the portfolio and run different type of risk analysis with the portfolio.

Following concepts are used: <br>
**Data Preparation** <br>
using data cleansing, indexing, sorting, rearranging columns and merging data frames.

**Quantitative Analysis** <br>
by computing and ploting of the following:
* Cummulative returns
* Daily standard deviation
* Annualized standard deviation
* Rolling standard deviation
* Correlation
* Covariance with respect to S&P 500 returns
* Variance of S&P 500 returns
* BETA and 
* Sharpe ratio

## How to run the script <br>
Clone the entire "whale-analysis" repository into a local folder by issuing the following command from gitbash <br>
```
$git clone https://github.com/rtapask/whale-analysis.git
```
Stay in the same gitbash directory and open Jupyter lab by issuing the following command from gitbash: <br>
```
$Jupyter lab
```

whale-analysis repository will be shown on the left hand side panel of gitlab. Navigate to whale-analysis -> Implementation and then open whale_analysis.ipynb in jupyter notebook and run each cells one after another.

## Important points to note <br>
Retain the folder structure as cloned from github. Else path set inside the notebook is not going to work. 
Hierarchy inside repository should look like following:
```
whale-analysis 
     |-------> Implementation 
        | 
        |---------------> whale_analysis.ipynby 
     |------> Resources 
        |---------------> whale_returns.csv 
        |---------------> algo_returns.csv 
        |---------------> sp500_history.csv 
        |---------------> goog_historical.csv
        |---------------> appl_historical.csv
        |---------------> cost_historical.csv
        |---------------> risk_free_rate.csv
     |------> README.md 
```



<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** rtapask@gmail.com