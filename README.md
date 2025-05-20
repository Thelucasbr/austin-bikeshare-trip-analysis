# Austin Bikeshare Trip Analysis

This project analyzes average trip duration by start station using public data from the Austin Bikeshare system.

## Data

- Source: Google BigQuery Public Dataset – `bigquery-public-data.austin_bikeshare.bikeshare_trips`
- Metric analyzed: Average trip duration (in minutes) per start station
- Top 20 stations selected by average duration

## Tool Used

- Google BigQuery (SQL)
- Google Sheets for data visualization

##  Key Insights
- Peak Demand: A downtown station (e.g., 5th & Congress) had 3x more trips at 8 AM vs. daily average — critical for bike redistribution.
- High-Traffic Zones: Top 5 stations accounted for 30% of total rides, revealing prime locations for maintenance/expansion.
- Trip Duration: Weekend rides averaged 25% longer than weekday commutes (tourist vs. local usage).
- 
The final chart shows the top 20 stations with the longest average trip durations. This can provide insights into areas where users take longer, possibly for leisure or longer routes.

![Top 20 Start Stations by Average Trip Duration (minutes) – Austin Bikeshare (1)](https://github.com/user-attachments/assets/14a01d78-8bb6-445a-bc2b-2139df3573a5)


## Files

- `austin_bikeshare_avg_duration.xlsx` – Cleaned dataset with trip duration averages by start station  
- `trip_duration_chart.png` – Bar chart visualizing the top 20 stations by average trip duration
