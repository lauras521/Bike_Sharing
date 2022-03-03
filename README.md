# CitiBike NYC Analysis to Determine Reapplication for Des Moines, IA

## Overview

### Purpose
A team is trying to determine if a bike sharing service would be successful in Des Moines, IA.  There is a large amount of data on CitiBike usage for New York City.  Tableau will be used to help the team visualize the NYC data and determine if they should undertake a similar project in Des Moines.  

## Results

### Analysis
Many visualizations were created to try and understand bike usage in New York City.  Details on the visualizations are below, but in general to get a big picture idea of how the bikes are used the following information was considered:

* CitiBike Subscribers vs. Customers
* Gender of Riders
* Duration of Trips
* Location of Bikes
* Time of Day for Rentals
* Day of Week for Rentals

### Visualizations

You can see the finished Tableau story with visualizations live here:
[link to dashboard](https://public.tableau.com/app/profile/laura.stock/viz/Module_14_Challenge_Des_Moines_Bikeshare/NYCCitiBikeStory?publish=yes)

Further explanations of each visualization in the story can be found below:

1. Pie chart shows how many of CitiBike's users are subscribers vs. non-subscribers/customers.
        
      * 81% of users in NYC subscribe to use the bikes.
      * 19% of users in NYC are customers who do not subscribe to the service.

2. Pie chart shows the gender breakdown of City Bike's users.

     * 65% of users in NYC are male
     * 25% of users in NYC are female
     * 10% of users in NYC did not disclose their gender

3. Line chart to how long users ride for.

     * The most frequent ride time for all users in NYC is 5 minutes.
 
4. Line chart to show how long users ride for by gender.

     * The most frequent ride time for women in NYC is 6 minutes.
     * The most frequent ride time for men in NYC is 5 minutes. 
     * Men have 3x more users than women at their respective peak frequent ride times.
     * After 45 minutes, men and women both do not have many riders.

5. Heat map to show peak times bikes are in use.
    
    * 6am-9am and 4pm-7pm are the highest use times Monday-Friday.
    * The weekends have steady usage during daylight hours.

6. Heat map to show peak times bikes are in use by gender.

    * Women and men have similar high volume ride times during the week and one weekends but in general men have higher usage. 

7. Heat map to show daily usage by customer and subscriber and gender.  

    * Men and women subscribers have higher usage on all days of the week over men and women customers.


<p align="center">
  <img src = https://github.com/lauras521/Bike_Sharing/blob/b563ab51c7d279431006ccadf07e783d0ed711d9/VisualizationPic1_4.PNG>
</p>

<p align="center">
  <img src = https://github.com/lauras521/Bike_Sharing/blob/b563ab51c7d279431006ccadf07e783d0ed711d9/VisualizationPic5_7.PNG>
</p>


## Summary
At a high level the CitiBike program in NYC has a high number of subscribers vs. customers and the majority of them are male.  The trip durations are short (peak usage ~5 minutes) and the peak times are around workday commutes and on the weekend.  

The team will need to understand the demographic of the Des Moines population to determine if this could be a viable business project for the city.  There are a number of things for the team to consider about the bike riding culture in Des Moines.  Below lists a few:

* Do people in the city enjoy bike riding?
* Is the city setup with sidewalks or good areas to ride on the street?
* Do people live within biking distance to and from work?  
* How populated are the areas near the city where people would be renting bikes?   
* Startup cost for the business and length of time to it would take the project to payout based on different use case scenarios.

Two additional NYC visualizations that would be helpful for the team are as follows:
1. A heat map showing the number of bikes in use vs. available based on time of day.  This could let you know if there were times when bikes actually weren't available to people.  During these times business might be even greater if bikes were in the correct location at the correct time and it could help indicate if more bikes are needed. 
2. Ride duration or distance until maintenance is needed and maintenance cost.  This can help you see how often maintenance is needed and how much money it will cost as well as help you understand how many bikes are in and out of service at a time.  
