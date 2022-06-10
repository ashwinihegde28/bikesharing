# bikesharing
Tableau - Data visualization using Tableau to present a business proposal for a bike-sharing company.

## Overview: 
The purpose of this analysis is to provide a business proposal that will convince investors that developing a bike-sharing program in Des Moines can be a profitable venture. Throughout the process, we use data that is publicly available from the NYC CitiBike program and "Tableau" to create visualizations. 

While the data is based on activity that occurred in New York City which is very different from Des Moines, we use our data expertise and critical thinking skills to build a story that can be presented to the investors. 

This uses data from August 2019 to build the analysis. It is assumed that there is more traffic or usage during the summer months compared to other times of the year in which weather can impact activity.

## Results:
## Deliverable 1:
Used Pandas to change the datatype of the "trip duration" column from an integer to a datetime datatype to get the time in hours and minutes.Once you change the datatype, you’ll export the DataFrame as a CSV file to use for the visualizations in Deliverable 2. The newly created tripduation column is name "new_tripduration" and renamed as "Tripduration." in tableau.

- Trip duration datatype is converted to datetime field<br>
![DataTypes](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/CitiBikeDF.PNG)<br><br>
![DataFrame](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/CitiBikeDF2.PNG)<br><br>

## Deliverable 2:
###  Number of Rides per Hour: 
There were total of 2,344,224 rides.<br>
<b>
![Total No Of Rides](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/TotalNumberOfRides.PNG)<br><br>
  
### Customer V/s Subscribers Utilization: 
  The Bike services were extensively used by Subscribers compared to their counterpart.  <br>
  ![users](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/CustomerVersesSubscriberPNG.PNG)<br><br>

### Gender Breakdown: 
  No of males utilizing biking service is dominant in this pie chart.<br>
  ![Gender Breakdown](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/genderBreakdown.PNG)<br><br>

 ### Peak Riding Hours in the Month of August:
  Based on the bar chart, the top riding hours during August in New York City is 5:00 p.m to 7:00 p.m.
  <br>
  ![August Peak Riding Hours](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/AugustPeakHours.PNG)<br><br>
  
  
  ### Average Trip Duration by Age:
  In general, the later the birth year, the longer the ride duration.<br>
  ![Average Trip Duration](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/AverageTripDuration.PNG)<br><br>
  
  
### Create the Checkout Times for Users: 
This graphing of the number of trips by duration shows that the vast majority of trips taken on CitiBike bikes are under an hour in length. <br>
![Checkout Time](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/Capture1.PNG)<br><br>
  
### Checkout Times by Gender: 
This graph displays that the male population used the bike service more compared to other populations. <br>
![Checkout Times by Gender](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/Capture2.PNG)<br><br>
  
### The Trips by Weekday for Each Hour: 
6-9 am and 5-8 PM are peak riding hours during the weekday and weekends rides are spread throughout the day. It also shows Wednesday evenings has less number of rides  <br> 
![he Trips by Weekday for Each Hour](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/Capture3.PNG)<br><br>
  
### Trips by Gender (Weekday per Hour):
Males are high users during the peak hours. The unknown gender hardly uses the bike services. <br>
![Trips by Gender (Weekday per Hour)](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/Capture4.PNG)<br><br>

### Trips by Gender and User Type (Weekday per Hour):
Graph displays males subscribers are the highest users followed by female subscribers.
<br>
![Trips by Gender and User Type (Weekday per Hour)](https://github.com/ashwinihegde28/bikesharing/blob/main/Resources/images/Capture5.PNG)<br><br>


  
  
  
  
  
## Summary
### Conclusion:  
- The data shows high activity of the bike sharing service in New York during the month of August 2019.
- Subscribers utilized this biking services to maximum compared to Customers.
- Male population were the majority to use biking compared to women.
- Bikes were utilised as an alternative mode of transport mostly during peak hours on weekdays and the hours were all distributed on weekends.

  
### Additional analysis would be beneficial by :
- To include analysis of the Bike sharing data for other months of the year against each metrics that we performed to see if the results are similar or different.
- Analysis can be performed on different b=nearby places or cities.
- During rush hours we can suggest alternative routes to avoid the traffic.
- Weather data can also be used to find the correlation between the weather and the rides. 
  
  

 




 


