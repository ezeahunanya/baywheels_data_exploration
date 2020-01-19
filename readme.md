# BayWheels Data Exploration Project
## by Eze Ahunanya


## Dataset

The dataset explored in this project is the bike trip data from BayWheels (Ford GoBike) for the years 2017 and 2018. The data set contains approximately 2.2 million trips. Before the analysis, I merged the separate tables into one dataset, and got rid of rows with missing values. I extracted the start hour, day of week and the month from the datetimes and put these variables into separate columns. I corrected all the ata types of eah colum and ordered appropiate variables such as the month.


## Summary of Findings


The key variable of interest, the trip duration, follows a unimodal distribution with a peak between 350 to 400. The start hours have  bimodal distribution with peaks at 08:00 and 17:00. The members birth years are unimoda and are skewed to the left meaning younger members predominantly use the platform. The younger members have a larger spread over the duration travelled and the longer journey are taken predominatly by younger members. The start hours became unimodal when looking at weekend data in contrast to the weekday. Males take shorter journeys compare to females on average and subscribers shorter journeys than customers.


## Key Insights for Presentation

I tweaked the transparency for the Duration vs Birth Year plot to a 0.1 (alpha). I also reduced the number of data points in this plot to make it clearer what area was highly dense. 