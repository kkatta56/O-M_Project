# O&M Project
This repository contains code and data visualizations pertaining to the stochastic weather window analysis of a Scottish offshore site. This data is useful for determining the optimal planning policies for the operations and maintenance (O&M) of floating multi-purpose platforms. The code in this project was written by Kaushik Katta in the R language and is based on Python code developed by [Taemin Heo](http://taeminheo.com) and [Dr. Lance Manuel](https://lancemanuel.netlify.app/) at the University of Texas at Austin.

## Visualizations
Wind speed data collected from an offshore site in Scotland from 2008 to 2017 was used for this project. Data was collected every six hours everyday for these 10 years. This wind speed data was used to determine a Beaufort Scale aalue for each day. The Beaufort Scale value for each day in each of the four quarters of the year is visualized below.

  ![BeaufortByQuarter](/images/BeaufortByQuarter.png)

 The difference between the different quarters of the year is more clearly seen by the boxplot below.
 
 ![BeaufortBoxPlot](/images/BeaufortBoxPlot.png)

This visualization shows the mean, minimum, and maximum Beafort Scale values for each quarter of the year between 2008 to 2017. The first and last quarters of the year depict a higher average Beaufort Scale value, meaning that the colder months have harsher wind conditions when compared to the warmer months.

## Reference Links
[Original Research Paper](https://github.com/kkatta56/O-M_Project/commit/d3824154b054cf30df9d7eec0bbdfdfcbf28d459)
