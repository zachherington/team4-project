# Team 4: Project Summary


## Project Title
* The Impact of Weather Related Changes on Rideshare Services in New York City
## Core Message
* We expect Manhattan rideshare activity to be affected by weather


## Data Resources
### Taxi Data Resources
* NYC Taxi Trip Records (Jan-June 2019)
* New York University Libraries: Neighborhood Name
* NYC Taxi Pickup Zones Data

### Rideshare Data Resource
* None
* Uber vs Taxi Research done by another analyst. Explains the limitation of Uber data. 
* https://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/

### Weather Data Resources
* Meteostat Historical Weather and Climate Data
* https://dev.meteostat.net/api/point/daily


## Data Cleaning and Exploration
### Taxi Data Exploration
* Ride activity by day
* Pickup zone research
![ride_vol_by_day_line.png](attachment:ride_vol_by_day_line.png)

### Weather Data Exploration
* Find the dates that had the most impactful weather
* Sort all weather data by each weather condition
* Store Top 10 days for each weather condition
![top_10_rain_days.png](attachment:top_10_rain_days.png)
![top_ten_max_temp_days.png](attachment:top_ten_max_temp_days.png)
![top_ten_min_temp_days.png](attachment:top_ten_min_temp_days.png)
![top_ten_snow_days.png](attachment:top_ten_snow_days.png)
![top_ten_wind_days.png](attachment:top_ten_wind_days.png)


## Data Analysis
### What areas of the map have the greatest number of ride pickups?
* Reduce our sample size
* Group ride activity by pickup zone
* Assign coordinates to each pickup zone
* Display ride activity in a heat map
![map%20%281%29.png](attachment:map%20%281%29.png)
![ride_vol_by_pickup_bar.png](attachment:ride_vol_by_pickup_bar.png)


### Are all rideshare services equally impacted by weather?
* Get a baseline average ride activity for each month.
* Merge ride activity of each day and month for the top ten weather conditions.
* Find the percent change in ride activity for each top 10 days. Repeat for each weather condition.
* Find the average change for each weather condition.
* Plot average change.
![percent_weather_changes.png](attachment:percent_weather_changes.png)
![change_in_ride_activity_for_each_weather_condition.png](attachment:change_in_ride_activity_for_each_weather_condition.png)


## Conclusion
* ...
* ...


## Future Considerations
#### Difficulties
* Extremely large datasets (8M lines per month)
* Finding historical weather datasets
* Assigning coordinates to pickup zones
* Lack of documentation for weather units 

#### Further research
* What is the impact of holidays and weekends?
* What other areas of NY had the greatest impact?
* What other forms of transportation should we include?
![percent_change_in_ride_activity_for_top_10_coldest_days.png](attachment:percent_change_in_ride_activity_for_top_10_coldest_days.png)