# The Big Squeeze: The Effect of Inflation on Housing, Employment and Spending power

## **Project Overview**

### *Package Requirements and Versions*

`pip install x` ; where 'x' is the package listed below:
* `python == 3.7.13+` 
* `pandas == 2.2.2`
* `hvplot == 0.7.3`
* `matplotlib == 3.5.1`

### *Files Navigation*
* Resources: Directory containing all images of plots created in Jupyter Notebook, and original csv data files
* Data: Directory containing all of the data sources used by the code
* `data_analysis.ipynb`: Data research using csv files, modules and API connections, and final dataframes and all graphs
  
  
### *Purpose of Use*   
Our team decided to research the effects of inflation during during a Pre- and Post-Pandemic date range, investigating true inflation percentage, annual inflation against a 2% average, consumer price index (CPI) reflects house related costs, unemployment rate, Correlation between inflation and the Housing cost, the impact of Housing cost on Foreclosures,[7] and [8].

The business question we hope to answer is: *if we can predict an increase or decline in housing costs when there is an inflationary period. Additionally, we hope to be able to answer if we can predict a rise or decline in the unemployment rate when there is an inflationary period.*

Our motivation for taking on this challenge is to find out if there is clear causation, or merely a correlation, between the effect of inflation on housing, unemployment and spending power.

We hope to find this data using the cost of housing prices from Data.gov, and the effect CPI and unemployment rates from the U.S. Department of Labor.

The periods of inflation analyzed include:
* Data Dates: 
  * Pre-Pandemic: 2015-2019
  * Post-Pandemic: 2020-2023


## Data Pre-Processing/Gathering Steps
Our team accessed inflation data from kaggle, U.S. Bureau of Labor Statistics and the U.S. Department of Labor.

We started by accessing CPI data from the U.S. Bureau of Labor Statistics. We used a pandas module called CPI to leverage the Consumer Price Index for north america. The data needed simple manipulation. First, it was necessary to define the start range of the data and the amount of periods in range. Then we calculated a 2% Inflation increase per year and plotted that on top of the CPI progression. We used the same dataframe to plot the actual inflation percentage against the average. These dataframes were plotted using line graphs and also a dynamic map using matplotlib. 

We then accessed time-series data in CSV format from Federal Reserve Economic Data and Kaggle. After acquiring the dataset, we cleaned it by renaming and filtering the columns to make the data more usable. Next, we sliced the dataframe to align the timelines, ensuring consistency across the dataset. We also handled missing data to address any gaps and performed normalization to prepare the data for comparison. These dataframes were plotted using scatter and heat maps using matplotlib. 

We then got data from the Bureau of Labor Statistics (BLS), which provides monthly and yearly stats through its public API or as downloadable datasets. The analysis looks at two main time periods: pre-pandemic (2015–2019) and post-pandemic (2020–2024). It focuses on two key metrics: the Housing CPI, which tracks housing costs, and the Unemployment Rate, which measures the percentage of unemployed people in the labor force. You can get the data by using the BLS API with specific series IDs and time ranges or by downloading it as a CSV or Excel file from their website. The goal is to process and visualize the data to spot trends before and after the pandemic, especially around housing inflation and unemployment changes. These dataframes were plotted using pie charts. 

[Xavier add a paragraph about accessing data]

After analyzing the above data and plots, we realized there were other data sources needed to as a supplement. As a result, we obtained references that backed our theories. 

## Visuals and Explanations

Using line graphs, we plotted the Pre- and Post-Pandemic Inflation Rate, and also the true inflation percentage. Below is a sample of each. All plots can be found in 'data_analysis.ipynb'.

![Consumer Price Index (CPI): Pre- and Post-Pandemic Inflation Rate](resources/content/lc_cpi_govtavg.png)
Consumer Price Index (CPI): Pre- and Post-Pandemic Inflation Rate

![Consumer Price Index (CPI): Pre- and Post-Pandemic True Inflation percentage](resources/content/lc_cpi_percentchange.png)
Consumer Price Index (CPI): Pre- and Post-Pandemic True Inflation percentage

[Mahhvid plots]

[Laxmi plots]

[Xavier plots]

## Additional Explanations and Major Findings

Our primary finding is that the correlation between inflation and housing is strong. 

https://www.investopedia.com/ask/answers/correlation-inflation-houses.asp
https://www.bankrate.com/real-estate/inflation-housing-market/#tips
https://www.whitehouse.gov/cea/written-materials/2021/09/09/housing-prices-and-inflation/

To begin our investigation, we took a look at ??

Through the first part of our investigation, we found little data that clearly indicates the correlation between inflation and housing ??espective markets.

Next, we took a look at ??

After analyzing our initial dataset, we discussed the other variables that we believe may play a role in our research, and decided that inflation should be the key indicator that we consider alongside what we initially gathered. Our data shows spikes in inflation that occur at the same time as the spikes we see in housing. In comparision for the Pandemic Era, we took inflation data from the 70's, suggesting that they are closely correlated. The same can be said for the graphs of inflation during the 2008 crash. Both show spikes shortly after the event and as inflation continues to rise, so does the cost of housing.

After analyzing inflation and housing, we decided to direct our attention towards housing and umeployment rates during ?

Our most interesting find comes when ?

We suspect the main culprit for our anomaly to be ?

## Challenges, Limitations and Future Development

The initial challenge was ?

After gathering and plotting all of the data, the limitations of this project are that ?

Limitations are clear pointers to future development. The relationship between all these factors is something that we could look at in the future. Now, if we are able to predict some of the future based on our current analysis, we could say that ?

## Conclusion

While ? may have had an effect on the ? we studied, we can/cannot reasonably conclude that ?

Understanding the role of inflation and interest rates in our data allowed us to ask ourselves "What other variables could be at play here?" Through further research and discussion we came up with: easing of COVID-19 restrictions, supply chain distruptions caused by the pandemic, America's level of involvement in each war, the seasonality of gas prices, the 2008 recession, and the political affliation of the sitting president are all potential variables that could affect what we are seeing. 

Ultimately, we gathered enough data to begin answering our business questions, and determined that predicting ?

One consideration that would make this all more clear, is ?

## References

* Yahoo Finance
* Nasdaq Data Link APIs:
  * Zillow
  * Federal Reserve Economic Data
* U.S. Energy Information Administration
* Federal Reserve Economic Data
* Coordinates of 50 states: https://gist.github.com/dikaio/0ce2a7e9f7088918f8c6ff24436fd035
* U.S. Bureau of Labor Statistics

## Team Members:

* Madhavi Nithianandam
* Xavier Figueroa
* Laxmi Atluri
* Chris Gilbert (Project Manager)
