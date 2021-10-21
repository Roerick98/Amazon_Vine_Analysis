# Amazon_Vine_Analysis
## Overview
For this project, I selected a data set from Amazon containing big data that consisted of reviews of selected video games. I then used Pyspark, an interface for Apache Spark in Python, to conduct the ETL process to learn more about this data set. First, I extracted the data from Amazon reviews via a pyspark script. Then, I transformed the data into a data set that would yield more useful information. Finally, I loaded the data set into an SQL database via Amazon RDS.
## Results
![Untitled](https://user-images.githubusercontent.com/35403433/138227531-9574b021-9317-467b-b06e-bae5d2316f86.png) <br />
- There were a total of 94 paid reviews and 40,471 unpaid reviews.
- There were a total of 48 5-star paid reviews and 15,663 unpaid 5-star reviews.
- The percentage of 5-star paid reviews to total paid reviews was 51.06%.
- The percentage of 5-star unpaid reviews to total unpaid reviews was 38.70%
## Summary
As expected, there was a higher percentage of 5-star reviews within the paid reviews data set when compared with the unpaid reviews data set. Although it is not extreme, there is still about a 12% increase in 5-star paid ratings. Although the amount of paid ratings is significantly less than unpaid ratings, there is no evidence to suggest the outcome would be different given a larger paid ratings data set.
