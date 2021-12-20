# Module_5_Challenge

# Overview of the analysis:

The purpose of this analysis is that using Python skills and knowledge of Pandas, we need to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we were requested to create a multiple-line graph that shows the total weekly fares for each city type. The idea is to provide V. Isualize with accurate information related to the performance of the service in different city types where Pyber operates.

# Results:

We have created a DataFrame with the information provided trying to summarize the information in a chart organized by city type, consiering the most important KPI to analyze the business: Total Rides, Total Drivers, Total Fares, Average Fare Rides and Average Fare Driver. What we get is the following information:

![Outcome of analysis](/resources/Analysis_results.png)

As we can see on the charte the driver of the income of Pyber is from the Urban area. This city type represents 62.7% of the overall income. Only 6.8% comes from rural area and 30.5%.

The dristribution is also similar in terms of rides, with 68.4% for urban areas, 26.3% in suburban and 5.3% in rural. 

It is important to notice that while in rural areas there is an average of 1.6 rides per driver this figures fall to 0,67 in urban areas and is 1.27% in suburban cities.

Considering that the rate is higher in rural cities this is generating that the drivers are more productive in those rural cities thant in the urvan ones. 

If we consider the evolution of the fares during the period of January to April we could see that it is quite stable over the time and with a high correlation between the different city types.

![Outcome of analysis](/resources/Challenge_fig.PNG)

We can observe an increase of the fares in the end of april for suburban areas that is not correlated with other city types and this could require a further analysis.

# Summary:

Considering the analysis performed we could suggest the following recommendations:

1- Reduce the number of drivers in the urban areas since the volume of rides per drivers seems to be low and with less drivers we could mantain the volume of fares. 

2- Explore what happen with more drivers in rural cities where it semms to be not enough drivers. We could launch some offers to become drivers of Pyber on those cities to increase the interest. 

3- We recommend to do a further analysis in the information trying to correctly understand the difference in average fare between the types of cities. A deeper analysis could help on developing a more professional pricing technique. 
