# PyBer_Analysis
## Overview of PyBer Analysis: 
---

The purpose of the analysis was to provide insights about the ride-sharing data for each city type so as to provide recommendations to the CEO V. Isualize. To begin with the data set for the various cities was sorted and analysed between the type of city. There are 3 different types of cities, Urban, Suburban and Rural. This analysis sought to provide a birds eye view of each city type without diving deep into the various cities with in theses city types. The analysis was summarized into a summary of findings or PyBer Summary Dataframe. A further analysis was carried out to examine the total weekly fare for each city type between Jan 1,2019 to Apr 28, 2019. The findings of this analysis was plotted into a multiple line chart which comes in handly whilst comparing the trend of how the total fare per week varied over January to April as well as the trend between the 3 city types.

--- 
## Results  
---

The results are brokendown between an analysis of the PyBer Summary Dataframe and a graphical analysis of PyBer weekly fare summary per city type for Jan 1,2019 to Apr 28, 2019.  

---
### Results of Pyber's summarized data:
---
![PyBer Summary Dataframe](https://github.com/fareenamughal/PyBer_Analysis/blob/main/Analysis/PyBer_Summary_df.PNG)

The summary 
1. Total Rides: Urban cities have the highest number of rides at 1,625 whilst total number of rides for Rural cities are at less than 10% of Urban city at 125 rides  
2. Total Drivers:Urban cities have the highest number of drivers 2,405 whilst Rural cities have 78 drivers only. It is possible that this disparity is due to the size of the cities as well as the population of the cities. The same is likely to apply for the disparity in total rides per city type.
3. Total Fares: Total fares for Urban cities is at almost $40K whilst Rural cities have approx. $4.3K (approximately 10% of total fares of Urban cities). This may also be attributed to population density but needs to be further investigated. 
4. Average Fare per Ride: Average fare per ride has an inverse relationship with Total number of rides, total number of drivers and total fares. Rural cities have the highest average fare per ride at $34.62 compared to Urban average fare per ride which is at $24.53. This may be due to stiffer competition between the higher number of drivers and rides in Urban cities. On the other hand the Rural cities may have demand for drivers and rides exceeding the supply thereby pushing the average fare per ride and per driver to much higher amounts compared to Urban or Suburban cities. 
5. Average Fare per Driver: This also has an inverse relationship to total rides, total drivers ana total fares. Urban cities have the lowest average fare per driver at $16.57 followed by Suburban cities at $39.50 and Rural cities leading at $55.49. This could be attributed to demand exceeding supply or could also be attributed to higher fares charged in general. There may be a reason for charging the higher fares, for instance the distances travelled may be longer and the trips may demand more attention by the drivers. This would need to be investigated furhter. 

---
### Results of the graphical analysis of PyBer weekly fare summary per city type for Jan 1,2019 to Apr 28, 2019:
---

![Revised NYC Citibike csv file](https://github.com/fareenamughal/bikesharing/blob/5082e0ac1987257a5e8bb1d4bd9399a949494e53/Images/screenshot_nyc_citibike_rev_csv_file.png)

Analysis of the multiple line graphs
1. Trend: It is evident from the line graphs that the total weekly fare for Rural and Suburban cities follows a fairly similar trend over the first 4 months of 2019. It is also evident that the trend for total weekly fares for Urban cities is different for Urban cities. For Urban cities from the second week of Feb. to end of Mar. there are alot of fluctions in the total weekly fares. Suburban cities collect the highest weekly fare from the 2nd to 3rd week of Feb. whilst rural cities collect the highest weekly fare from the 3rd to 4th week of March. Overall second to third week of feb shows an increase in weekly fares, possibly due to valentined week! 
2. Urban cities fluctuations between 2nd week of Feb. to end of March needs to be investigated. It is possible that there was more demand for drivers due to a higer need for rides but Urban cities could perhaps not fulfill this demand due to limited supply of drivers. This should be investigated further to provide more meaningful analysis.
3. The multiple line graph chart ignores other factors as population, demograpgics, density etc. It would be advisable to plot a bubble chart taking population or weather into consideration in addition to the above.
4. I have assumed a box and whisker plot for each city type did not show any outliers and the data used was within the acceptable range. 

--- 
## Summary 
---

I would recommend that Pyber introduce a loyalty program which would award user points that could be redeemed on future rides. This would ensure that people call Pyber's drivers to book their rides as opposed to riding with drivers from Pyber's competitors. Another recommendation would be to reallocate the oversupply of drivers in Suburban and Rural cities to Urban cities expecially during the 2nd week of Feb. to end of March as we notice alot of fluctuations in the weekly total fares for Urban cities. Furthermore, Pyber needs to move the driver supply away from the less profitable routes to the more profitable routes. Some routes may just not have sufficient demand to necessitate a fixed supply of drivers. This information can be obtained from the individaual city analysis. I would also recommend that Pyber incentifies its drivers by perhaps having a quarterly bonus award for the highest performing driver. This would ensure that drivers are eager and ready to take rides as and when called for. These step would encourage overall growht at Pyber leading to increasing and maintaining the customer base due to increased loyalty, drivers rewarded based on performance thereby leading to motivated drivers and growth interms of increase in total weekly fares i.e. positive growth in the bottow line figures!. 


