# 🏙️ CitiBike NYC 🚴
*Data Visualization with Tableau* 
## Background  
CitiBike is the nation's largest bike share program, with 20,000 bikes and over 1,
300 stations across Manhattan, Brooklyn, Queens, the Bronx and Jersey City. It was 
designed for quick trips with convenience in mind, and it’s a fun and affordable 
way to get around town.  The fortunate news is that there is an ideal tool for this
need, called Tableau
Tableau is one of the most popular and effective tools for data visualization in 
todays' professional world.   It allows data visualization professionals to create data 
stories that are visually appealing and easy to undersand for a non-technical audience.  In 
addition, Tableau provides the tool to create powerful analytic dashboards and tell 
a clear story that can be easily shared with others.   Tableau can be simple, 
requiring, little-to-no-coding, or quite complex, requiring some experiences to 
write custom code in.  Tableau is very flexible.  

### Purpose
For this project we are creating a data visualization for the New York City.   The 
idea is to analyze the data, see the operations of the business and become informed 
about how well the bike sharing program really works.   The initial information is 
that the program is so successful, we could expand it to other cities.  With a 
strong, clear story, backed-up by data we can create a proposal on how the business 
could work in other cities as well.     

**The Tableau story of the NYC CitiBike** can be found in the following link: 

[NYC Citibike Story Board](https://public.tableau.com/app/profile/jk.rotter/viz/NYCBikeStoryBoard/NYCCitiBikeStory)


## Resources
This page contains the following information: 
-  Data Source:
   -  CitiBike Trip History Data from August 2019 - .csv file in folder
-  Software:
   -  Tableau Public 2020.3   
-  Languages & Environment:
   -  Pandas, Jupyter Notebook, Python 3.7  

### Overview
On first page of the story is the dashboard in the **Tableau Public** platform that contains basic overview 
information about the data provided in the csv data set.   The purpose of this page is to become familiar with the data 
and to introduce the audience what kind of data we will be dealing with in the further analysis.  
This page contains the following information: 
  -  Type of business, time frame and location of the data; CitiCike, New York City, for the Month of August, 2019.  
  -  Number of total rides:  2,344,224
  -  Customer type: Customers and Subscribers 

<p align="center">
  <img width="400" height=400" src="https://github.com/mjrotter4445/NYC-Bike-Sharing-Program-Dashboard/blob/main/images/0BasicInfo%20Dashboard.jpg">
</p>

## 1. Checkout times for Users
This graph has the number of checkout bikes (number of trips) on the y-axis and trip duration on the x-axis.  
X-axis is divided into hours and minutes for more analysis.  
<p align="center">
  <img width="400" height=300" src="https://github.com/mjrotter4445/NYC-Bike-Sharing-Program-Dashboard/blob/main/images/1CheckoutTimesbyUsertype.jpg">
</p>

## 2. Checkout times by Gender
This graph has the number of checkout bikes (number of trips) on the y-axis and trip duration on the x-axis.  
The color indicates the number of trips with orange representing male, blue for female, and red representing 
the unknown genders.     The highlite of the chart is that males checkout bikes at a much higher fequency than 
female or unknown gender, especially between 1 hour to 1-17 hour durations on long trips.     
 <p align="center">
  <img width="400" height=300" src="https://github.com/mjrotter4445/NYC-Bike-Sharing-Program-Dashboard/blob/main/images/2aCheckoutTimesbyGender.jpg">
</p>

## 3. Trips by Weekday per Hour with Length of Trip 
This graph shows number of checked out bikes on the y-axis and trip duration on the x-axis.   
<p align="center">
  <img width="400" height=300" src="https://github.com/mjrotter4445/NYC-Bike-Sharing-Program-Dashboard/blob/main/images/2btripsbyweekdayperhrwithlength.jpg">
</p>

## 4. Trips by Gender by Weekday and by Hour
This graph shows the number of trips per hour and per weekday that bikes were checked out.  The hours are on the y-axis and weekdays on the x-axis. The colors speak to the volume.   We can see that the busiest times are in the moring hours on weekdays from 6am to 9am and in evening hours on weekdays between 5pm and 7pm.   Also Saturdays and Sundays are business in the middle of the day between 10am and 6pm. Again, males are the most frequent users.   
<p align="center">
  <img width="400" height=300" src="https://github.com/mjrotter4445/read_me_working_file/blob/main/Images/4%20Trips%20by%20Gender%20by%20Weekday%20by%20hour.jpg">
</p>

## 5. Trips by Gender by Weekday
This graph shows the number of trips per hour and per weekday that bikes were checked out, by user type (customers and subsribers) and by gender.   The weekdays and user type are on the y-axis and the gender on x-axis.   For subscribers, males has the highest
number of trips especially on Thursdays and Fridays, followed by trips on Monday and Tuesdays.    
<p align="center">
  <img width="400" height=300" src="https://github.com/mjrotter4445/read_me_working_file/blob/main/Images/5%20trips%20by%20Gender%20by%20Weekday.jpg">
</p>

## 6. Bike Utilization
This graph indicates, with dots, the accumulated trip utilization (by hours and minutes using the calculated field).  Small bubbles are approx. 200,000 time units, Medium bubbles are approx. 300,000 time units, Large bubbles are approx. 2,000,000 time units.  From this visualization and using the bike ids, maintenance and replacements can be planned.     
<p align="center">
  <img width="300" height=300" src="https://github.com/mjrotter4445/read_me_working_file/blob/main/Images/6%20Bike%20Utilization.jpg">
</p>

## 7. Top Starting Locations & Top Ending Locations 
These next two graphs show the most popular starting and ending locations.   The larger bubbles represent the larger numbers.  
<p align="center">
  <img width="800" height=200" src="https://github.com/mjrotter4445/read_me_working_file/blob/main/Images/7%20top%20starting%20and%20stops.jpg">
</p>

## Summary
The story of the NYC CitiBike starts off with the basic information 
about the users and the trips they take.  From the first page we can 
learn a lot about users for bike share company and helps 
us understand data in further analysis and operations.   Business 
Decisions made from the data might include these categories:  

**Bike Maintenance** plays a big role in bike share business. Heat maps 
are a great visualization for large amounts of data and provide us clear 
story about the data.    The charts suggest taht the least busy times 
are bettween 11pm and 5am.   These would be the best times to stagger 
the maintenance work throughout the fleet of bikes.  


**Customers and Subscribers** 
Customers are the most important part in the business.   CitiBike NYC 
is doing well because they understand the different users types 
(customers and subscribers) and their very different habits and needs. 
With this information, the best decisions can be made to support all 
needs and keep the busines growing.  

**Gender**
The charts reveal that there are very differenct behaviors for each gender. 
A deeper dive into the details could help formulate a marketing strategy and grow
the business.  

**Trip Duration** 
The most common checkout time is between 3-8 hours.  The data lets us study the
one way trips and two way trips too.   We can strategize the pricing structure and
possibly provide day passes or other pricing options for 2 way trips.    

**Further Analysis Recommendations**
I would use this dashboard with a test group.   I would see what questions came up with the audience
and further develop the details, based on that feedback.   
Some ideas might include: 
   - Weather impact on Utilization (especially on low volume days, possibly remove those outliers).
   - Covid impact on Utilization from 2019 before, during 2020 conditions and also 2021 to understand any possible new needs that have surfaced.  
   - How many bikes are and the "end of life" and would need to be replaced.  Additional counts and charts could help with this capital planning work.  
 

