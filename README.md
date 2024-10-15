# US Accidents Exploratory Data Analysis
This project presents an exploratory data analysis (EDA) of US Accidents data sourced from Kaggle. The goal is to provide insights into accident patterns and trends, which could be useful for accident prevention and understanding the factors leading to traffic incidents.

### Dataset
Source: Kaggle - US Accidents
Size: 4.2 million accident records from February 2016 to December 2020.
Data Fields: The dataset contains 49 columns with information like accident location, time, weather conditions, and more. It does not include data from the state of New York.

###  Key Columns:
ID: Unique identifier for each accident
Severity: Accident severity level (1-4)
Start_Time and End_Time: Time of the accident
City, State: Location of the accident
Temperature(F), Weather_Condition: Weather data during the accident
Various boolean flags indicating road conditions, like Amenity, Bump, Traffic_Signal, etc.


###  Installation and Setup
Clone the repository.

Install the necessary dependencies:
Download the dataset:
Load and explore the data:

### Data Cleaning

Before diving into analysis, some cleaning tasks were performed:

Handled missing values in columns like End_Lat, End_Lng, and Precipitation(in).
Converted the Start_Time column to datetime for time-based analysis.

### Exploratory Data Analysis (EDA)

The EDA focuses on understanding the following:

City-wise Distribution: Cities like Houston and Los Angeles have the highest number of accidents.
Time Analysis: A large percentage of accidents occur between 6 AM - 10 AM and 3 PM - 6 PM, correlating with peak traffic hours.
Weather Conditions: We analyze how different weather conditions impact accident severity.
Weekend vs Weekday Trends: Accidents tend to occur later in the day on Sundays compared to weekdays.

### Visualizations

The project includes various visualizations created using matplotlib and seaborn:

City-wise accident counts (bar chart)
Hourly distribution of accidents
Weekday vs weekend accident patterns
Monthly trends for accidents over the years

### Insights

This analysis provides valuable insights into the timing and conditions under which accidents are more likely to occur. These patterns can inform policies for road safety improvements and help design better traffic management systems.

### Future Work

Deeper analysis of weather data and its impact on accidents.
Time series forecasting for accident trends.
Identifying high-risk locations and times for targeted interventions.

### Limitations

The dataset does not include data from New York state.
Some data from early years (2016-2017) is incomplete.

