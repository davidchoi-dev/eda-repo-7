# Stock-Trading Backtesting and Data Analysis

### Develop profitable asset allocation portforlio better than traditional All-weather portfolio

In this project, we developed the asset allocation portforlio in order to secure stable funds after retirement. This project based on Data Mining and Economic statistics.

team: 이태헌, 김희주

### Backtesting
* We downloaded stock trading data and extract close data. Then we analyzed correlation between 5 indexes and profitability & volatility.

#### Steps for backtesting 
* Define strategy
* Back Test using historical data
* Result Analysis
* Develop portfolio based on analysis
* Compare profitability,volatility prediction


### Data Sources : [Investing.com](https://www.investing.com/)
Index 

    Index: SP_Index, Interm_Index, Longterm_Index, Commodity_Index, Gold_Index
    feature : weekly data
    period: 1996.07.01 ~ 2020.06.29(25 years)
    
ETF    

    ETF: SPY, IEF, TLT, DBC, GLD
    feature: weakly data
    period: 2006.06.26 ~ 2020.06.29(15 years)
    
### Define a Problem
* High Relative Poverty Rate for the Elderly in Korea
![1](https://user-images.githubusercontent.com/68367134/97185204-20308d80-17e3-11eb-80ba-af56ae278924.png)


## Data Processing

* comparison rate of cumulative return by asset types
![Screen Shot 2020-10-26 at 23 34 28](https://user-images.githubusercontent.com/68367134/97185701-bbc1fe00-17e3-11eb-9d31-46d8ad0e3895.png)


### Portfolio
- portfolio_1 : stock 100%
- portfolio_2 : stock 60% + long-term bond 40%
- portfolio_3 : All_Weather : stock 30% + long-term bond 40% + mid-term bond 15% + commidity 7.5% + gold 7.5%


