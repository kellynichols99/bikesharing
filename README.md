# bikesharing

<h1>Project Overview</h1>
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.
For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

<h1>Resources</h1>

- Data Sources: 201908-citibike-tripdata.csv, citibike_tripdata_cleaned.csv,

- Software: Tableau

- Dependencies: Pandas
<body>
<h1>Summary</h1>

<h3> Deliverable 1: Change Trip Duration to a Datetime Format Resampling Models to Predict Credit Risk</h3>
<p>iUsing Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.</p>

<h3>Deliverable 2: Create Visualizations for the Trip Analysis</h3>
  
<p>Using Tableau, create visualizations that show:
How long bikes are checked out for all riders and genders.
How many trips are taken by the hour for each day of the week, for all riders and genders.
A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.</p>

Checkout Times for Users Viz:
  
<img src="https://github.com/kellynichols99/bikesharing/blob/main/Resources/Time%20for%20Users.png">

Checkout Times by Gender Viz:
  
<img src="https://github.com/kellynichols99/bikesharing/blob/main/Resources/Times%20by%20Gender.png">
  
Trips by Weekday for Each Hour Viz:
  
<img src="https://github.com/kellynichols99/bikesharing/blob/main/Resources/Trips%20by%20Weekday%20for%20Each%20Hour.png">

Trips by Gender (Weekday per Hour):
  
<img src="https://github.com/kellynichols99/bikesharing/blob/main/Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png">

User Trips by Gender by Weekday:
  
<img src="https://github.com/kellynichols99/bikesharing/blob/main/Resources/User%20Trips%20by%20Gender%20by%20Weekday.png">

<h1>Challange Summary</h1>
The bike sharing service is very popular in Manhattan, and is most popular with male users in the morning. However, the popularity did not last. Standard rush hours are themost popular times Monday - Friday and midday on Saturdays.
  
<p>
NOTE: I had several technical issues along the way with the Challenge. I worked with the AskBCS tutors and they were not able to resolve the issue as well. (see screenshot from resources file). You can see this in visualizations, that have identifying numbers and not the specific genders listed. The saved Tableau file for some reason has only one visual though there were not errors when saving. 
</p>

[link to dashboard](https://public.tableau.com/app/profile/kelly.nichols/viz/Mod14Challenge_16577743740020/UserTripsbyGenderbyWeekday)

