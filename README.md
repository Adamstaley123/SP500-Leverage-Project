# SP500-Leverage-Project
Analyzing historic returns since 1980, I attempt to analyze and build models to understand the performance of Daily Leveraged Assets. 
The current code is broken up into 5 blocks, which I describe below:
- #1 - Source credit and project info
- #2 - Data cleaning and wrangling
- #3 - A repository for functions I use throughout the project
- #4 - Begin analysis of the leveraged assets using the functions created in section 3. Using log scales, price performance, and rolling return graphs to help interpret results for several rules-based strategies. 
- #5 - Analyze risk using Kde plots of price level change within the given years, and begin models to describe under what conditions the leveraged assets outperform the non-leveraged assets. I build a logistic regression model to classify returns and use k-means clustering to group return types. 
Further potential areas of research:
- Build a more generalized approach that allows a machine learning model to determine its own "rules" to maximize returns and minimize losses.
- Define a loss function for that model that focuses on avoiding rapid high-magnitude changes in price without loss of generality. 
- Quantify the "real cost" of leveraged ETFs - up to this point, we have modeled the price return of assets at a theoretical amount of leverage with no cost. Etfs like UPRO and SSO incur costs, making this analysis limited for practical investing purposes:
  - Lack of dividends in return analysis
  - Expenses and fees charged by these ETFs
  - Cost of borrowing incurred by these funds
- Concretely quantify the risk associated with the daily leveraged ETFs in the long term in terms of drawdowns and other factors. 

