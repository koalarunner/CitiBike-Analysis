# Tableau Assignment - Citi Bike Analytics

## Background

(Fictitious - for Education Purposes Only - I am not actually an Analyst for CitiBank or CitiBike)

As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, I am now responsible for overseeing the largest bike sharing program in the United States. In my new role, I will generate regular reports for city officials looking to publicize and improve the city program. 

## Task

I aggregated the bike share data from August '15 - '18. No other time periods were included. These are my findings from the data. 

* How many trips have been recorded total during the chosen period?

Total Trips Taken: 6,530,382

* By what percentage has total ridership grown? 

Total Riders 
2015 - 1,179,044
2016 - 1,557,663
2017 - 1,816,498
2018 - 1,977,177

Ridership Growth by Period 
'15 - '16 - 32.1% 
'16 - '17 - 16.6%
'17 - '18 - 8.845% 

Total Growth Between '15 - '18 
67% 

* How has the proportion of short-term customers and annual subscribers changed?

Years '15 - '16 - Proportion of short-term customers to subscribers dropped. In 2015 - 18% of total riders were short-term customers. In 2016, only 14% of riders were short-term customers; a 4% decrease in short-term riders. During that period, for every 1 short term customer, there were 4.3 subscribers. 

In '16 - '17 - Proportion of short-term customers to subscribers dropped again, but that proportion remained steady from '17 - '18. In 2016 - 14% of riders were short-term customers, and that percentage remains the same through '17 and '18. 

Although total ridership increased, the proportion of subscribers to short-term customers remained around 6 to 1. 

* What are the peak hours in which bikes are used during August? 

Start Time: 8-9AM, 5-6PM 
End Time: 8-9AM, 5-6PM 

Bike usage in all years studied showed that both start and end times majorly peak between the hours of 5 - 6PM. ~1.2M bikes start and ending during that time.

In second place is 8-9AM. 

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)

1	Pershing Square North
2	West St & Chambers St
3	E 17 St & Broadway
4	W 21 St & 6 Ave
5	12 Ave & W 40 St
6	Broadway & E 22 St
7	W 20 St & 11 Ave
8	Broadway & E 14 St
9	Cleveland Pl & Spring St
10	8 Ave & W 31 St

These stations are near mass-transit hubs and popular tourist attractions, making them natural locations for bike pickup. The most popular location is Grand Central Station. Riders come into the city and rent a CitiBike to cover the "last mile" between their entry to the city and their ultimate destination. 

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

1	Pershing Square North
2	West St & Chambers St
3	E 17 St & Broadway
4	12 Ave & W 40 St
5	Broadway & E 22 St
6	W 21 St & 6 Ave
7	W 20 St & 11 Ave
8	Cleveland Pl & Spring St
9	8 Ave & W 31 St
10	Broadway & E 14 St

These stations are the most popular end points for CitiBike rentals for the same reasons as they are popular starting points. They are near mass-transit hubs and popular destinations. Bike renters are either returning their bikes from their day in the city, or dropping the bikes off after coming from a different part of the city to reach public transit or visit those popular destinations. 

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

According to the data, the actual bottom starting places for a journey seem to be various tech shops. Since this is most likely due to maintenance work being done on the bikes, I will discount these starting places. I expanded the data to include the bottom 150 results to get a clearer picture of areas where bike journey's are less likely to begin. These neigborhoods include: Harlem, Astoria, and Brooklyn. 

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

As above, the same relative pattern shows. Harlem, Astoria, and Brooklyn are neighborhoods in which bike riders are less likely to end a ride. 

* Today, what is the gender breakdown of active participants (Male v. Female)?

Years '15 - '18 
Male - 63% 
Female - 22%
Unknown - 13% 

* How effective has gender outreach been in increasing female ridership over the timespan?

It has been marginally effective. Female ridership has increased by 4% (of the total rides/year) over this time period.

Female Riders as a Percentage of Totale Rides in a Given Year: 

'15 - 20%
'16 - 21%
'17 - 23%
'18 - 24% 

* How does the average trip duration change by age?

Young riders ages 17 - 21 seem to take longer trips than young adults or middle age adults. Potentially due to more free time available, and longer distances between activities or commitments around the city. 
Older riders ages 84 - 100 seem to take longer trips than all other riders on average. Potentially due to having time for leisure, while also riding more slowly than other riders. 
Outliers are middle age riders ages 32 and 50 exactly. These two ages take longer rides on average than most riders. It's unclear why these specific ages have a higher than average trip duration. 

* Which bikes (by ID) are most likely due for repair or inspection in the timespan? 

It's unclear what the tolerances for usage the bikes have. There are several bikes that have >4M Trip Duration Seconds. In fact one bike in particular has 5,114,297 Seconds, which is ~59 Days of straight usage. I would suggest servicing any bike that has over 4M seconds of use over the analyzed period, as this only represents 1 month over the course of 4 years. 

BIKE ID: 
17928
17799
15462
25945
21148

* How variable is the utilization by bike ID?

There is a correlation between the number of records an individual bike has and the sum of its trip duration. As the number of records/bike fall, so too does the sum of the trip duration. There are several outliers that show heavy usage on a relatively smaller number of trips, but that could be caused by a malfunction in the system, random chance that bike was chose for an exceedingly long ride a number of times, or due to not returned for a number of days. 