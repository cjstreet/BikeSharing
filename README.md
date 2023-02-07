# BikeSharing
Using Tableau to analyze and visualize bikeshare data in NY. 

## Objective:
The main objective is to show investors the most important relevant data from the bike-sharing program in New York, so that they will invest in the Des Moines bike-sharing business.

The following questions will need to be answered:
1. How variable is bike utilization? 
2. What might the key costs be in a bike-share business?
3. What is the breakdown of annual subscribers vs. short-term customers?
4. What are the peak hours for bike rentals? 
5. What are the highest-traffic locations? 
6. When and where do people use Citi Bike?
7. Whats the average duration of a trip by age?
8. Which genders utilize bike-sharing?
9. How does the Citi Bike program work during the month of August in New York City?
10. What are the most popular starting and stopping stations?
11. How often are bikes used? How often do they need repairs?


<hr>


**Steps:** 
1. Import citibike dataset into Jupyter NB. 
2. Use Pandas to convert `tripduration` column from an integer to a datatime datatype.
3. Export converted citibike dataset to a csv file. 
4. Import the dataset into Tableau.
5. Build various visualizations and adding interactive filters
    - a. The length of time that bikes are checked out for all riders and genders.
    - b. The number of bike trips for all riders and genders for each hour of each day of the week.
    - c. The number of bike trips for each type of user and gender for each day of the week.
6. Add these worksheets and dashboards to a Tableau story that details the overall analysis to pitch to investors.


## Resources
- Data Source: https://citibikenyc.com/system-data, 201908-citibike-tripdata.csv
- Software: Jupyter NB, Pandas, and Tableau Public Edition

## Results:

## Interactive Dashboard
<a href="https://public.tableau.com/app/profile/christy.street/viz/CStreet_RideSharing/NewYorkStory?publish=yes">Invest In Bike-Sharing</a>

## Summary: 

In New York, there are over 2 million rides on the Citi Bike-Sharing program. The average user is a male subscriber that uses the bike to most likely commute to work. The busiest times for rides are around 8am and 5pm, Monday thru Friday. The average duration of a ride is about 5 minutes. It appears that the bikes are a vital resource to the people of New York. Depending on the sustainability of the program financially this would be a good investment for any large condensed urban city. Des Moines may not have a similar urban infrastructure as New York and if riders had to commute over 5 minutes to work they might not use bike-sharing.

Two additional visualizations should be considered:
1. Produce a visualization that would give us the average age of riders. 
2. Although, the data isn't available in the dataset, it would be valuable to know how much money the program is generating and spending. 

