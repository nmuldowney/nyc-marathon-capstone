## New York City Marathon Analysis - Capstone Project

## Table of Contents
* [Motivation](#Motivation)
* [Data Questions](#Data-Questions)
* [Known Issues and Challenges](#Known-Issues-and-Challenges)
* [Tools Used](#Tools-Used)
* [Data Sources](#Data-Sources)
* [Tableau Dashboard](#Tableau-Dashboard)


### Motivation:

I have been a runner for over 18 years  and it is a huge part of who I am and what has motivated me throughout my life. I ran the NYC marathon 4 years ago and want to analyze the results data over the last 5 years to see how the results vary over time. In addition, I will see if  there are any correlations with age groups and gender. I will also explore more behind the results and pull in other datasets to uncover insights about the runners and potential trends that correlate with the weather on race day and the runners' home country's economy.


### Data Questions:

1. How do the NYC marathon results vary over the last 5 years?
2. Are there trends in age group and gender with performance?
3. Is there a correlation between weather on race day and performance?
4. Is there a relationship between runners' finish times and GDP Per Capita of their hometown?



### Known Issues and Challenges:

I have run into some data issues as far as gathering all of the NYC marathon results. After web scraping the results for the last 5 years, I was only able to obtain results for the first 10k runners in each of these races. There was an api limitation on the website. This race has over 50k runners per year. I decided to do my analysis using the first 10k finishers of each race per year.
Another challenge I ran into was that my GDP per capita data had some null values. I filled these with the most recent valid observation in the data for the given country.


### Preview of Insights:

Here you can see a graph of the average finish times grouped by sex. There are steadily faster finish times for both male and female runners over the last five years. In addition, there is a consistent spead of about 6-9 minutes between the two sexes each year. 

![Average Finish Time By Sex](/images/avg_time_by_sex.png)


### Tools Used: 

* Python - BeautifulSoup, Pandas
* Tableau
* Visual Studio Code
* Git/Github
* Google Slides
* Excel



### Data Sources:

  - New York City Marathon results:  https://www.nyrr.org/tcsnycmarathon/results/race-results
  - World GDP: https://data.worldbank.org
  - Weather: https://w2.weather.gov
	     https://www.ncdc.noaa.gov



### Tableau Dashboard:
  https://public.tableau.com/profile/nicole.muldowney#!/vizhome/NYCMarathonAnalysis-CapstoneProject/Story1
