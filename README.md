# (Flights Report in the USA )
## by (Ugochukwu Okpoko)


## Dataset

>The Flight data report flights in the United States from 1987 to 2008. I have limted this project's review to most recent reports (3 years) from 2006 - 2008 due to the size of the dataset. 

This [link](dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2FHG7NV7&version=&q=&fileTypeGroupFacet=&fileAccess=&fileSortField=name&fileSortOrder=desc) is the repository for all the required data.

There are 5.2 million US flights in the dataset scheduled between 2006 and 2008 from January to April. The dataset has 20 variables, most of which are categorical, with month, day, and departure hour with the following levels;

    month: January, February, March, April.

    day: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday.

    crsdephour : 01, 02, 03, 04, 05, 06, 07, 08, 09, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 00.


## Summary of Findings

During the exploration, I observed that 44,110 (1%) flights were cancelled from 5.2 million scheduled flights from 2006 - 2008 within January to April. The least number of flights were scheduled for 3am (0.00002%), April, and Saturday, respectively. Some Airlines, demonstrated 100% flight completion rate, examples are; Southwest > American Airways > Expressjet Airlines > American Eagle > Continental Air.

Most of the scheduled flights range from 200 - 800 miles, so a log transformation on distance helped to clarify the distribution of distance.

California and Texas were the busiest states, Georgia State recorded the most number of cancelled flights. Mesa Airlines had most cancelled flights, particularly due to Carrier reasons. 

All flights scheduled for 3am were completed for every Airline and Airport.

## Key Insights for Presentation

The main features of interest in the `US Flight Data` are reviewed based on the questions below:

- What are the preferred times or days for flights to occur?
- What are the best Airlines?
- Are there any perfect period for the worst airline?
- Does distance have impact in flight completion? 

