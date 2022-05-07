# Housing Home Average Values Analysis in past 20 Years

In this project we are working with the zillow data set and google api for the our obervations and analysis. Home Value prices are significantly increasing with the start of 21st Century, and here we did some analysis within united states Averages of the home values and reant pricing. 

## Data Sets & API

* We used this data set from zillow and downloaded all our CSV's from here [Zillow Research Data Sets](https://www.zillow.com/research/data/).
* We used the google API link [Google API](https://developers.google.com/maps/documentation/geocoding/requests-geocoding)

## Average Home Values By all states in UNITED STATES

 * The following image captures the TOP 5 Average home value by different criterias:

  ![Top 5 States Average Home Value](ScreenShots/top_5_states_ar_chart.png)
  
  
 * Create a Bar graph and boxplot and also the heatmaps to compare all state from 2000 to end of march 2022 base on home value price. It is showing us the Price varies by state and we noticed that Arizona is the cheapeast from all the 50 sates and Hawaii is the most costly. 
  
  ![Top 5 States Average Home Value](ScreenShots/Bar_chart&#32;all&#32;states.png)
  ![All States Average Home Value](ScreenShots/Average_US_Home_Value_map.png)
  
  ![All States Average Home Value](ScreenShots/BoxPlot_allstates_averagehomevalue_ALI.png)
  ![Region Scatter Average Reny Value](ScreenShots/Avg_City_Home_Value_map.png)
  
  
 # Comparision of the Average home in California by past 3 years
 
 * Pie Chart showing the average price of year 2020, 2021 and 2022 in California

  ![All States Average Home Value](ScreenShots/California_pie_chart_fenny.png)
  
 # Anovotest in Average home value
 * p-value greater than 0.05. If the p-value is large (> 0.05), it indicates weak evidence against the null hypothesis.As a result, the null hypothesis is not rejected.Thus for a hypothesis with a p-value greater than 0.05, the null hypothesis is not rejected, and the alternative hypothesis is not accepted. This means that the results of the research/ study are not statistically significant.
 * p-value less than 0.05. If the p-value is small (< 0.05), it indicates a piece of strong evidence against the null hypothesis. As a result, the null hypothesis is rejected. Thus for a hypothesis with a p-value less than 0.05, the null hypothesis is rejected, and the alternative hypothesis is accepted. This means that the results of the research/ study are statistically significant.

* Based on the TOP 5 STATE VALUE FROM JAN 2000 TO MARCH 2022, does not have any significant IN PRICE.
* F_onewayResult(statistic=122.0636293024792, pvalue=8.814967969996069e-89

![All States Average Home Value](ScreenShots/Top5StatesBox&#32;Plot.png)

* Based on the TOP 2 STATE VALUE FROM JAN 2000 TO MARCH 2022, have significant IN PRICE.
* F_onewayResult(statistic=13.028463629177644, pvalue=0.00033578407607901705

  ![Top 2 States Average Home Value](ScreenShots/Ali's_2top&#32;states&#32;Average_home&#32;VAlue.png)
  
  ![Top 2 States Average Home Value](ScreenShots/Top2StatesBox&#32;Plot.png)

* Based on the TOP 5 CITY IN CALIFORNIA VALUE FROM JAN 2000 TO MARCH 2022, does not have any significant IN PRICE.
* F_onewayResult(statistic=206.69941708214913, pvalue=6.112212677528717e-138)
  
  ![Top 2 States Average Home Value](ScreenShots/Top_5Cisities_california_ali.png)
  ![Top 2 States Average Home Value](ScreenShots/Box_plot_by_city_ALI.png)

  
  # Average Rent Values Analysis
  
  * The bar chart shows the comparison of rent averages by regions in the United States.
  
   ![Region Average Reny Value](ScreenShots/rent_average_byregion_luis.png)
   
  * The scatter plot shows the comparison of rent averages by regions in the United States.
  
   ![Region Scatter Average Reny Value](ScreenShots/scatterplot_byregion_luis.png)
   

![Region Scatter Average Reny Value](ScreenShots/Rent_Average_Value_map.png)
