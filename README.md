# bikesharing
# Project Overview
#### For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
1. #### Show the length of time that bikes are checked out for all riders and genders
2. #### Show the number of bike trips for all riders and genders for each hour of each day of the week
3. #### Show the number of bike trips for each type of user and gender for each day of the week.
#### Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors. The deliverables of this project includes:
- #### Deliverable 1: Change Trip Duration to a Datetime Format
- #### Deliverable 2: Create Visualizations for the Trip Analysis
- #### Deliverable 3: Create a Story and Report for the Final Presentation

## Resources
- #### Data Source: `201908-citibike-tripdata.csv` 
- #### Data Tools/Software: Jupyter Notebook and Tableau

## Deliverable 1: Change Trip Duration to a Datetime Format
> Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.
#### Requirements
1. #### The data in the "tripduration" column is converted to a datetime datatype and has the correct time format.
![6](https://user-images.githubusercontent.com/76136277/113462767-9370a800-93f0-11eb-9d80-a630646e1357.PNG)

2. #### The DataFrame is exported as a new file without the index column.
![7](https://user-images.githubusercontent.com/76136277/113462810-b733ee00-93f0-11eb-89ff-8fbdb4296102.PNG)

## Deliverable 2: Create Visualizations for the Trip Analysis
> Use Tableau to create visualizations of how long bikes are checked out for all riders and genders, how many trips are taken by the hour for each day of the week, for all riders and genders and, a breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
#### Requirements
1. #### There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
![1](https://user-images.githubusercontent.com/76136277/113463182-6cb37100-93f2-11eb-8f8e-71154bd4d22c.PNG)

2. #### There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
![2](https://user-images.githubusercontent.com/76136277/113463184-71782500-93f2-11eb-9e92-c25710032a2f.PNG)

3. #### A heatmap is created showing the number of bike trips for each hour of each day of the week.
![3](https://user-images.githubusercontent.com/76136277/113463508-0deef700-93f4-11eb-885b-ff38a6eada43.PNG)

4. #### A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.
![4](https://user-images.githubusercontent.com/76136277/113463207-8f458a00-93f2-11eb-9917-8073b142df79.PNG)

5. #### A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.
![5](https://user-images.githubusercontent.com/76136277/113463518-16473200-93f4-11eb-811d-f08524d8ab5d.PNG)

## Deliverable 3: Create a Story and Report for the Final Presentation
> For this part of the Challenge, you’ll create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis you did in the module and in Deliverable 2.
#### Requirements
1. #### You must use the five visualizations that you created in Deliverable 2.
![8](https://user-images.githubusercontent.com/76136277/113463387-68d41e80-93f3-11eb-89e3-a811bffd53c0.PNG)
![9](https://user-images.githubusercontent.com/76136277/113463389-6d003c00-93f3-11eb-812c-69027e91bf05.PNG)

2. #### You must use at least two visualizations that you created in this module.
![10](https://user-images.githubusercontent.com/76136277/113463430-96b96300-93f3-11eb-94b7-2988392a5fa9.PNG)
![11](https://user-images.githubusercontent.com/76136277/113463433-991bbd00-93f3-11eb-86fa-7030cf7cbd6d.PNG)

## Results
> Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
- #### With the analysis, we can conclude that we have more than 80% subscribers and less than 19% non-subscribers. Also, there are more male than female customers.
![12](https://user-images.githubusercontent.com/76136277/113463672-3e836080-93f5-11eb-981c-6a7535aed805.PNG)

- #### Checkout times by gender and users were at the peak in the 5th hour.
![13](https://user-images.githubusercontent.com/76136277/113463850-6626f880-93f6-11eb-8af1-e3c4bce2e310.PNG)
 
- #### More trips were made on Thursdays between the hours of 5pm - 6pm.
![14](https://user-images.githubusercontent.com/76136277/113464018-b6eb2100-93f7-11eb-8569-dc5b9457594e.PNG)

## Summary
> Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
#### In summary, the citibikers trip had more male customer than the female. Also, most of the trips were made on Thursdays between the hours of 5pm and 6pm (88,887 trips in total by all customer type and gender. A reasonable amount of trips were made on Tuesdays as well between the hours of 5pm and 6pm  with a total of 72.883 trips.
#### Two additional visualization
1. #### Top 10 Stations (start of trip)
2. #### Top 10 Stations (end of trip)
