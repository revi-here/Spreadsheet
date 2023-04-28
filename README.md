# Bellabeat
<b> by Revathy Thiyagarajan  

Understand the trends from the given Fitbit users dataset and provide insights on various features to help the marketing team of Bellabeat.

![Bellabeat](images/BB-Logo.png 'Bellabeat')   

*** 
## Resources  
1. Data Source   : FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius):  
2. Data analysis : Google sheets  
3. Visualisation : Google sheets  
  
***  
## Limitations
1. The data available corresponds to daily activity of only 33 users and even lower for other categories like sleep and weight.  
2. Weight not analyzed as it corresponds to only 8 users.  
3. The data is biased as it doesn’t show details about the gender, age group, location of the user.  
4. The data is collected in 2016.

## Steps  
1. Understand the general trend shown by the user in terms of - steps, distance and calories.  
2. Compare the data for weekday and weekend.  
3. Study how active the users are for various intensity level activities.  
4. Correlation with average distance covered and steps walked and calories burnt. 

# Exploratory Data Analysis.  

## Understanding the trends.  

<b>Average Distance.    
![Average Distance](images/histogram_avg_distance.png 'Average Distance')    
<b>Average steps.   
![Average Steps](images/histogram_avg_steps.png 'Average Steps')   
<b>Average Calories.   
![Average Calories](images/histogram_avg_calories.png 'Average Calories')   
  
Members show a general trend of covering 5 miles in 10000 steps and burning around 1500 calories on an average.  
      
## Weekday vs Weekend Comparison.  
     
<b>Average Distance - Weekday vs Weekend.    
![Average Distance](images/Average_distance.png 'Average Distance - Weekday vs Weekend.')    
<b>Average steps - Weekday vs Weekend.   
![Average Steps](images/Average_Steps.png 'Average Steps - Weekday vs Weekend.')  
<b>Average Calories - Weekday vs Weekend.   
![Average Calories](images/Average_Calories.png 'Average Calories - Weekday vs Weekend.')    
      
The above graphs show that the users are more active in weekends(2 days) than weekdays(5 days).   
  
## Percent of different active range. 
### Active range.  
![Active level](images/Active_range_comparison.png 'Active range')   
- Members in general do very light activities which constitutes around 70% of their overall activities.   
- Moderate activities constitutes only 10% which can be improved by introducing many challenges of moderate intensity.  
 
## Above average distance.  
![Above and Below Average distance ](images/Comparison_Chart.png 'Above and Below Average distance')   
  
- Members who walks above average distance (5 miles) show increase in number of steps and number of calories burned.   

# Conclusion.  
  1. Members are more active in weekends. So we can introduce more Challenges/rewards for weekday activity.   
  2. Very light activity is the most preferred(70%) among users. Promote more moderate intensity activity.  
  3. More the distance, more calories and more steps. Notification introduced when average distance is reached.  
 
# Techniques Used.   
   * IF clause.  
   * Conditional formatting.  
   * Pivot table.  
   * VLOOKUP.   
   * Charts.

