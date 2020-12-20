# PROPOSAL FOR BIKE SHARING BUSINESS IN DES MOINES IOWA
## The following analysis uses data from the Citibike bike sharing business in NYC to gather insight into the potential for a successful bike sharing business in Des Moines Iowa.  
### Background
After discovering New York City on a more intimate basis by using Citibike rentals on a visit, our clients are interested in exploring how this experience might translate to a bike sharing business in their own home town of Des Moines Iowa.  They have gathered some potential investors who are interested in seeing some statistical analysis of the Citibike data to see if this is a feasible proposal. 

###  Data Provided
Citibike ride data including the following fields:
1. Trip Duration
2. Start Time
3. Stop Time
4. Start Station ID, Name, Latitude, Longitude
5. End Station ID, Name, Latitude, Longitude
6. Bikeid
7. Usertype - customer versus subscriber
8. Birth Year of rider
9. Gender of rider

## Introduction

It might seem like a big leap to compare bike sharing data from a large metropolitan city like NYC to a midwest city like Des Moines.  However, I will show that there are certain similarities in the bike sharing business which suggests that Des Moines may very well be a good target for this business.  There are two main points that make the cities similar:
1.  They both have similar flat topography which is conducive to bicycling.
2.  They both have many miles of paved bicycle paths through their downtown areas.  Des Moines has 63 miles of paved bike paths through their downtown according to the city website.  NYC has been increasing bike lanes significantly over the past few years as more bicycling is catching on.
3.  They are both cities with commuters. 

Unfortunately, they also share another similarity which must be considered.  They are both in the top 10 most dangerous bicycling cities in the US according to a study published by "Your Local Security."  This study indicates that the danger is largely due to minimal bicycle safety laws in place.  So before embarking on a bike sharing business, any investors should explore liability issues that may come up due to the danger of riding bikes in cities like these.

### Statistical Analysis

####  Customer Type

The first statistic I explored was the type of customers.  If it is tourists mainly using the bikes, then the business model probably wouldn't be successful in Des Moines since that is not such a big tourist destination.  

![](https://github.com/xactuary/bikesharing/blob/main/CustomerType.PNG)  

This pie chart displays how more than 80% of Citibike customers are subscribers rather than one time users.  This is an indication that over 80% of riders are using the bicycles regularly which implies they are not tourists but a continuous source of income to the business.  

####  Peak Hours of Use

The next statistic I examined to determine what type of business this might be is to look at the peak hours of use.  If it is mostly tourists, then the peak hours will be during the middle of the day when the bikes would be used for sight seeing rather than commuting.  

![](https://github.com/xactuary/bikesharing/blob/main/PeakHours.PNG)
  
This graph indicates that the peak hours are between 5 pm and 7 pm (17-19 on 24 hour clock).  In addition, there is a surge at the 8 am time slot.  These are the commute hours and definitely not the tourist hours.  This is another indications that there is a big commuter usage of the bicycles.  

#### Days of Week

Another statistic of interest is the usage by hour by the day of the week.  The following plot is a heat map showing the most heaviest used hours by days of the week.
  
![](https://github.com/xactuary/bikesharing/blob/main/HeatHours.PNG)  

So not only are the commute hours the most popular, but the commuter days are also the most heavily used at those times.  So Monday, Tuesday and Thursday at 5 pm are showing the most usage.  In addition, however, there is usage on the weekends which implies there is a leisure target market as well.  With Des Moines having paved bicycle paths, this may also be a leisure activity that locals and visitors might pursue on the weekends.  

#### Gender

We may clean some insight as well into how the bicycle usage varies by gender of rider.  This first chart displays how there are significantly more males using the bike sharing program than females.
  
![](https://github.com/xactuary/bikesharing/blob/main/Gender1.PNG)  

This chart reveals that more than twice as many bikes are being used by males than females at the peak hours.  This can give the business an idea that any marketing should be targeting males.  In Des Moines, the population breakdown of male versus female is 49.3% according to to Census.gov data.  This compares to NYC where the proportion is only 47.7%.  So there may actually be an advantage to Des Moines in capturing the commuter market because there are proportionately more men.

#### Gender by Hour of Day

The following heat map displays how the significant commute time usage is by males rather than females.  There is a small surge in the female population in the commute hours but no where near as much as in the male population.  This may imply that females are more likely using the bicycles for leisure activity whereas males are using it for commuting.  This again would give the business some insight into how to target the marketing of the product.

![](https://github.com/xactuary/bikesharing/blob/main/GenderTripsPerHour.PNG)  

#### Gender by Weekday by Usertype
 
This chart narrows down the information specifically to weekday by gender split by usertype.  This makes it very clear that the males are preponderance of the midweek subscriber commuters whereas the leisure customers are spread a little more equally between males and females.  

![](https://github.com/xactuary/bikesharing/blob/main/GenderbyWeekday.PNG) 

#### Duration of Usage

Now that we have looked at what types of users we would expect to see and perhaps what population to target commuting purpose to versus leisure purpose, let's look at how much usage the bicycles are getting overall to see if this is a viable business.
  
This graph shows the overall average usage by number of bicycles.  

![](https://github.com/xactuary/bikesharing/blob/main/AvgDuration.PNG)  

This graph reveals that there is a huge number of bicycles being used for a significant amount of time with an average usage of 5-6 hours.  If the business charges by the hour, then there is a decent potential for income.  In addition, if this long usage is due to commuters, then this significant usage suggests that there could be longetivity to the subscriber model keeping a steady income coming in.  

I would suggest also looking at this statistic of trip duration by usertype to see the difference in usage for subscribers (commuters) versus customers (leisure riders) to further establish this hypothesis.

























