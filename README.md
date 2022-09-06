# ACM Research coding challenge (Fall 2022) : Analysis of cars sold per year and top car makers

PROBLEM STATEMENT AND INTENT:

Analysing and visually graphing the number of cars sold per year and noting the top car manufacturers along with value for money rating to predict pricing potential.   

APPROACH:

1. Firstly, I imported multiple modules to integrate the CarsForSale database with python. Imported modules: numpy, pandas, os, matplotlib.pyplot and operator.
2. I made induvidual functions to generate a scatterplot, bar graph and pie chart to analyse isolated parts of the data.
3. The scatterplot describes the value for money rating for the purchased cars over the years as contained in the CarsForSale data set. As seen in the scatterplot, the number of outliers in the data has increased over the years. This may be due to lower general satisfaction of customer purchases or may even be a result of a lack of data in years before 2010.
4. The generated bar graph describes the number of cars sold per year and explains the sales trend from 2001-2022. As we can infer from the graph, an increase of sales has occured after 2010. This may be due to the fact that cars after 2010 became more of a necessity or the fact that new cars became more expensive to purchase by the general consumer. Preowned car sales peaked exponentially in 2019 but fell drastically low in 2020. This may have been due to external factors including the pandemic or the rise of smart cars and the shortage of silicon based microchips.
5. Lastly, the the generated pie chart further explains the distribution of sales from the top 5 companies in the market. Here we can see that the most market share in the preowned cars sector is from BMW. However, the data provided seems to provide an inconclusive inference due to the market sales being extremely close and within a margin of error of 2% from each other. By having more clean and reliable data perhaps a more conclusive result can be produced.

OBSERVATION AND FUTURE STEPS:

After a preliminary analysis, we can say that the amount of data provided may be used to draw logical conclusions from the years 2010-2020, provided that more data can be recorded from the years that are missing it. Additionally, predictive analysis is a possiblity from the data provided in the CarForSale file. With further clean data, a machine learning model can be made in order to predict future pricing and customer satisfaction based on purchases and customer reviews. 
