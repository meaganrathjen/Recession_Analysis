# The impact of the 2008 recession and the COVID recession on the industries

## Project Proposal
As you know, all stocks are affected by the 2008 recession and the COVID recession.We decided to took a closer look at recessions to see how different industries and portfolios of stocks performed throughout these recessions. We analyzed by choosing 5 stocks from each industry. 
We have compared the 2008 recession and the recent COVID recession, try to find out how they performed both recessions various portfolios based in 5 different industries perform both prior to and during their respective economic downturns.
Also we determined the risk and volatility associated with each industry portfolio and how correlated were the industry portfolios to the S&P 500.

- Entertainment: Imax Corporation, Disney, Netflix, Comcast, Sony
- Fast Food: McDonald’s, Wendy’s, Yum! Brands Inc., Domino’s Pizza, Jack in the Box Inc.
- Tech: Amazon, Apple, Microsoft, Google, Intel Corp.
- Travel/Transportation: Expedia Inc, Booking, American Airlines, Delta Airlines, SouthWest Airlines
- Energy: Exxon Mobil, BP, ConocoPhillips, Chevron, Total SE


## Finding Data & Data Cleanup & Analysis
Data was originally pulled using  Yahoo Finance by utilizing Pandas DataReader to pull the adjusted close data.
In order to better understand the impact of the 2008 recession and the COVID recession on the industries, we calculated Sharpe Ratios, Correlations, Rolling Averages , Variance, Covariance, Beta for leading up to the 2008 recession, during the 2008 recession, leading up to the COVID recession and during the COVID recession from the data.

Findings about our studies are as follows.

 - Expected Returns

    Prior 2008: Tech is most volatile, offered highest expected return but also had the most downside risk. Entertainment also had lots of downside in this period, but without as much upside. Everything else is relatively normal in terms of standard deviation and correlation to S&P 500. 

    ![ER PRIOR 2008](https://github.com/crcrawfo1/Project1/blob/main/Photos/returns/returns_before_2008.PNG)

    During 2008 Recession: Tech was once again the most volatile and had the highest upside. Every other sector moved in correlation with the S&P 500.

    ![ER During 2008](https://github.com/crcrawfo1/Project1/blob/main/Photos/returns/returns_during_covid.PNG)
   
    Prior COVID: Not as much apparent volatility compared to the 2008 data sets. Fast Food had the highest upside point in early 2019. Tech (along with the entire market) fluctuated up and down quite a bit at the end of 2018. 

    ![ER PRIOR COVID](https://github.com/crcrawfo1/Project1/blob/main/Photos/returns/returns_before_covid.PNG)

    During COVID: Every industry experienced wild market fluctuations in March – May of 2020. Energy and Fast Food had the highest volatility on both ends of the spectrum. Surprisingly, Tech was not volatile at all during this timeframe relative to the S&P and other industries.

    ![ER During COVID](https://github.com/crcrawfo1/Project1/blob/main/Photos/returns/returns_during_2008.PNG)
    


 - Annual Risk Findings
 
    Prior 2008: Tech (0.377) has the highest risk, while Fast Food (0.176) has the lowest risk of industry specific portfolios. S&P 500 (0.103) has lower risk than all portfolios.

    ![AR PRIOR 2008](https://github.com/crcrawfo1/Project1/blob/main/Photos/annual_risk/annual_risk_before_2008.PNG)

    During 2008: Tech (0.558) still has highest risk however every other category gained in riskiness at a higher multiplier. S&P 500 jumped to 0.352 and Fast Food actually had less risk than the S&P at 0.325. 
    
    ![AR During 2008](https://github.com/crcrawfo1/Project1/blob/main/Photos/annual_risk/annual_risk_during_2008.PNG)
    
    Prior COVID: Entertainment carrier highest risk at 0.283 followed closely by Energy and Tech. S&P was the lowest risk at 0.149. 

    ![AR PRIOR COVID](https://github.com/crcrawfo1/Project1/blob/main/Photos/annual_risk/annual_risk_before_covid.PNG)
    
    During COVID: Unsurprisingly, Energy (0.642), Transportation (0.582), and Fast Food (0.552) had the three highest risk factors as people dealt with the lockdowns by not traveling or going outside which led to little demand for these services. Surprisingly, Entertainment (0.331) had a lower annualized risk than the S&P 500 (0.342) for this time period. 

    ![AR During COVID](https://github.com/crcrawfo1/Project1/blob/main/Photos/annual_risk/annual_risk_during_covid.PNG)


