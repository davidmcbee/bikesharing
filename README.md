# bike sharing
## Overview and Purpose
Kate and I went on a vacation to New York last summer. We had a wonderful time and a major factor to having such a great trip was our use of Citibike. Using rented bicycles we were able to explore the area on our schedule. Further, using these rental bikes, we were able to get to know the people and see sites that were not part of the main tourist stops.  We also saw many people using Citibike to commute to and from work. We quickly realized that this business would thrive in our home town of Des Moines, Iowa.

This analysis and presentation looks at how Citibike works in New York with the hope you can see how it will be successful in Des Moines.

## The Analysis.
The analysis was accomplished by looking at Citibike data for the month on August, 2019. We choose August assuming it is one of the peak months; tourism in addition to normal commuting. The original data file is available here (  ).
The data needed some conversion so, using python and Pandas we changed the trip duration to an actual date time object. This way the calculations and displays would come out as expected. This cleaned and converted file is available here (  ).

### Resources
For this analysis we used Python in Jupyter Notebooks along with the Pandas library. For the display we used Tableau.

For the following analysis please use this link to follow along in Tableau. Feel free to use the filters to drill down as desired. (https://public.tableau.com/profile/david.mcbee#!/vizhome/CitiBikes_Challenge/CitiBikes?publish=yes).

## Results
### Trip Duration
The first graphic to bring to your attention is Trip Duration. This graphic shows the number of bikes compared to the hours and minutes used. The most bikes used, 3,005 at the peak are used in the 5 hour range.
### August Peak Hours Usage
Compare this to the second graphic, the August Peak Hours Usage. For august 224,566 bikes were used in the 1700 (5pm) time frame. 
### Number of Bikes by Duration Broken Out by Gender
To see just who is using these bikes, look at the Number of Bikes by Duration Broken Out by Gender graphic. This repeats graphic one but by gender. The obvious point here is that males are the predominant user but I thought it interesting that the trip duration curve for females followed the same shape, though at a much lower level.
### Trips Broken Out by Day
So, know that we know the durations and degree of use, which is a lot, lets look at when the bikes are used. For this please see the Trips Broken Out by Day graphic. This heatmap shows a couple items worth knowing:
1. The heaviest weekday use is during commuting hours.
 2. Weekend use is heaviest on Saturday and the hours are spread out during the day.
 ### Trips Brooked Out by Day and Gender
 This view is further broken down by gender in the Trips Brooked Out by Day and Gender graphic.  The usage by females follows the male usage but to a lesser degree. This further reinforces the times used, commuting hours for weekdays and during the day on weekends.
 ### Trips Broken Out by Day, Gender and User Type 
 The Trips Broken Out by Day, Gender and User Type shows:
 1. Males use during the week, especially Thursday, is the heaviest and these users are predominately Subscribers - the commuters.
 2. Subscribers also use the bike on weekends.
 3. Customer's heaviest use is on the weekend.
 You can also get a better understanding of males to females by looking at  the pie chart in the lower right. 1,530,272 males as compared to 588,431 females.
 ### Bike Repairs
 The last graphic, Bike Repairs provides details on how many times a single bike is used, which in turn, indicates maintenance needs. One bike was used 479 times. Given this and the usage times it is recommended that maintenance be done at night.
 
## Summary
Given the fact that this is a very successful business in New York, which has a population of 8.399 million people, while Des Moines has a population of 216,853. At 37% of New York, if Des Moines had 37% of the 2,344,224 bike trips for August that New York has, this would amount to 867 trips. This number is quite sufficient to fuel a prosperous business.

If you agree, I recommend we dive deeper. I believe we can do better then New York by understanding the following:
1.  How many trips are booked by more then one person for a particular trip. I think we can increase female ridership for weekend trips by marketing this to couples and families. 
2.  We can market this to companies themselves to increase commuter use. To do this we would need to understand the distance that commuters are comfortable biking.
3.  We can market this to businesses. There is probably a synergistic positive effect to businesses by these bikers in New York. By looking at the most common routes we could let bikers know about those businesses on those routes. Wine tasting and  ice cream shops are the two that come readily to mind. 

 
 


