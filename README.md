# NYC-collision-analysis
Analysis of accident in NYC 🚙

## Project Overview
This project is focused on analyzing and deriving insight to mitigate accidents in New York city. This data contain information from all police reported vehicle collision.

![NYC collision overview](https://github.com/user-attachments/assets/f2bbf15b-d68d-47f9-8772-9dc1b292684f)

## Data source
The primary data source for this project is 'NYC collision.xlsx' and it contains information about the date of collision, type of vehicle, street name, contributing factor and others.
[Dataset]()

## Tool
- Microsoft Excel
  - [get tool here](https://www.microsoft.com/en-us/microsoft-365/excel)

Microsoft Excel is the tool used through out this project right from getting the data, cleaning and analysis.

## Data cleaning
1. I reviewed the data type of the fields in the data set and changed them appropriately.
2. I created new fields like days of the week, month, year and hour of day using excel functions.
3. Handled missing values.

### Data manipulation
Using excel functions to get the year, month name..
```excel function
YEAR(collision date)
```
```
MONTHNAME(collision date)
```
```
DAYNAME(collision date)
```
```
HOUR(collision date)
```

## Analysis
1. Comparing the rate of collision per month

Accidents frequency increased in the first three month of the years. Highest number of accidents occur in March followed by January.
![image](https://github.com/user-attachments/assets/b72c24db-5aac-41d0-b808-54dd5d952ac8)


2. Break down of accident frequency by day of week and hour of the day that accident occured.

Friday was the day of the week with the most accident. Regardless of the day of the week, the hour when the most accidents occured was in the morning at 4.am and start decreasing from 5.am.
![image](https://github.com/user-attachments/assets/1e8219e1-fd07-42aa-9d48-b8fc96722306)

3. The street with the highest number of accident reported most.

BELT PARKWAY had the highest accidents from the top 10 streets and BROADWAY had the second highest percentage, 17% of the reported accident occured on BELT PARKWAY.

![image](https://github.com/user-attachments/assets/43bcc272-b422-442c-8f12-531a0c129a34)


4. Most contributing factor to the reported accidents and fatal accident specifically.

The factors contributing to the accidents were not Specified for 30% of accidents. Driver Inattention/Distraction accounted for 29%.


### Recommendation

1. Consider adding age as part of the accident report to determine if distracted drivers fall into a certain age group.
2. NYC police should focus on implementing policies to reduce unspecifird and driver inattention.
3. To avoid collision in NYC, signal should be placed in every turn and lane change.
4. Drivers should maintain a safe distance while driving.



