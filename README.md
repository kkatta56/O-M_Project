# O&M Project
  This repository contains code and data visualizations pertaining to the stochastic weather window analysis of a Scottish offshore site. This data is useful for determining the optimal planning policies for the operations and maintenance (O&M) of floating multi-purpose platforms. The code in this project was written by Kaushik Katta in the R language and is based on Python code developed by [Taemin Heo](http://taeminheo.com) and [Dr. Lance Manuel](https://lancemanuel.netlify.app/) at the University of Texas at Austin.

## Seasonal Variation Visualizations
  For this project, we wanted to show that there were seasonal differences in the data. Wind speed data collected from an offshore site in Scotland from 2008 to 2017 was used for this project. Data was collected every six hours everyday for these 10 years. This wind speed data was used to determine a Beaufort Scale aalue for each day. The Beaufort Scale value for each day in each of the four quarters of the year is visualized below.

  ![BeaufortByQuarter](/images/BeaufortByQuarter.png)

  The difference between the different quarters of the year is more clearly seen by the boxplot below.
 
 ![BeaufortBoxPlot](/images/BeaufortBoxPlot.png)

  This visualization shows the mean, minimum, and maximum Beafort Scale values for each quarter of the year between 2008 to 2017. The first and last quarters of the year depict a higher average Beaufort Scale value, meaning that the colder months have harsher wind conditions when compared to the warmer months.

  The safe weather windows when the safety threshold is set to a Beaufort Scale value less than or equal to 5 for each quarter of the year between 2008 and 2017 is shown in the figure below.
  
  ![BinaryTimeSeriesQuarter](/images/BinaryTimeSeriesQuarter.png)
  
  This visualization shows that there are significantly longer periods of safe weather windows during the warmer months than the colder months. There are clear seasonal variations shown qualitatively through the above visualizations
  
## Markov Decision Process
A Markov Decision Process (MDP) framework was created to help find the optimal policy that minimizes the overall cost that occurs due to unsuccesful O&M activities and the loss of revenue from lack of O&M.

## Reference Links
