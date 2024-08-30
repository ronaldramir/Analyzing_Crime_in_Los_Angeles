# Analyzing_Crime_in_Los_Angeles


## Hour with the Highest Frequency of Crimes
* Objective: Determine which hour has the highest frequency of crimes.
* Approach:
+ Extract the hour from the TIME OCC column.
+ Count the frequency of crimes per hour.
+ Identify the hour with the maximum frequency.
* Result: The variable peak_crime_hour will store the hour with the highest number of reported crimes.
* Visualization: A bar plot shows the number of crimes by hour of the day.
## Area with the Largest Frequency of Night Crimes
* Objective: Identify the area with the highest frequency of crimes committed between 10 PM and 3:59 AM.
* Approach:
+ Filter the data for night crimes.
+ Count the frequency of crimes per area.
+ Identify the area with the maximum number of night crimes.
* Result: The variable peak_night_crime_location will store the area with the highest number of night crimes.
* Visualization: A horizontal bar plot shows the number of night crimes by area.
## Number of Crimes by Victim Age Group
* Objective: Analyze the number of crimes committed against victims across different age groups.
* Approach:
+ Define age bins and labels.
+ Categorize ages into these bins.
+ Count the number of crimes in each age group.
* Result: The victim_ages Series will show the frequency of crimes for each age group.
* Visualization: A bar plot displays the number of crimes by victim age group.

## Key Points in the Code:
## Libraries: The script imports necessary libraries such as pandas, numpy, matplotlib.pyplot, and seaborn.
### Data Loading: The dataset is read using pd.read_csv().
### Data Processing:
* Hours are extracted and counted.
* Night crimes are filtered based on hour.
* Age groups are created and counted.
* Plotting: Various plots are generated to visualize the results.
