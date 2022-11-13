# Student_Data_Analysis

## Overview
Today we are helping the chief data scientist for a city school district, Maria. We must prepare standardized test results for analysis and reporting, then provide insights on performance trends and patterns. With these insights, we will be able to inform both individual schools and the city school district on pperformance. 

## Results
When we were presented with the data set, we received it in the form of a <a href="Resources/new_full_student_data.csv">csv file</a>. After doing some quick checks, we found that there were 1968 reading scores and 982 math scores that were not filled in to the dataset. After dropping the rows with the blank data, we checked for duplicates. We were able to drop 1836 rows with duplicated data. To make our analysis easier, we had to convert the grade column to an integer by removing "th" from the values. 

After cleaning up our data, we were now ready to analyze. 

We started with a basic summary statistic of the entire dataset. using the .describe() function, we were able to get the statistics. 

<p align="center">
  <img width="" height="" src="Resources/summary_statistics.PNG">
</p>
