# bikesharing
Create visualizations using Tableau to analyze New York bike sharing data.


## Overviw of the project 

For this analysis, we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.



This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

1- Deliverable 1: Change Trip Duration to a Datetime Format

2- Deliverable 2: Create Visualizations for the Trip Analysis

3- Deliverable 3: Create a Story and Report for the Final Presentation


## Resources

- Data :
- Software : Python, Jupyter, Tableau Public.

## Summary

**Deliverable 1**

We used Pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes. After we export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2 [updated_data_frame].

**Deliverable 2**

Using Tableau, we created visualizations that show:

- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

1- Checkout times for users

2- Checkout times by gender

3- Trips by weekday per hour

4- Trips by gender (weekday)

5- User Trips by Gender by Weekday

**Deliverable 3**

In this deliverable we are trying to create a story for the Citi Bike data:

1- First story giving an overview about the citi bike data.

  - There were over 2.3 million rides for the month of August 2019.
  - 81% of the users were subscribers. 65% of the users were confirmed males and 25% were confirmed females.
  - There is a wide range of the age of the users. Younger users tend to use the service for longer rides.
  - Top ride starting locations are in the most touristic and busy areas, as we see here in Manhattan.

![story1]

2- Second story regarding the type and gender of Citi Bike users: 

  - We notice that the majority of city bike users are subscribed male with more than 81% subscribed and 65% male.

![story2]

3- Third story is regarding the data trips: we can notice that most rides are taken between 5 pm and 7pm by subscribed users during weekdays.

  - Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.
  - The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.


![story3]


4- Fourth story regarding august data analysis by time frame that shows that during summer time the peak of use of citi bike starting and ending was between 5 pm and 7pm.


![story4]

5- Fifth sory tell us about the top starting and ending stations: its shows that pershing square north is the most used station in Manhattan, followed by E17 St & Broadway.

![story5]
