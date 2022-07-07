# pyber_analysis

# Overview
The purpose is to analyze ride sharing data at PyBer and to get insight into performance based on city type.

1. Ride sharing summary DataFrame by city type
2. A multiple-line chart of total fares for each city type.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter Notebook, Python 3.7.13, Visual Studio Code 1.68.1

## Results
The link to the script of ride sharing analysis.<br>
[Ride sharing analysis](/PyBer_Challenge.ipynb)<br>

### DataFrame showing total rides, total drivers, total fare, average fare per ride, and average fare per driver as per city type
- Total rides, total drivers and total fare increases with city type from rural, suburban, and urban.
- Average fare per ride amd average fare per driver decreases with city type from rural, suburban, and urban.<br>

<figure>
    <figcaption>Summary DataFrame of rides, drivers, and fares per city type</figcaption>
    <img src="/Resources/pyber_ride_summary.png" width="1335" height="260"
         alt="Summary DataFrame of rides, drivers, and fares per city type">
</figure> <br>

<figure>
    <figcaption>Bubble chart of ride summary data</figcaption>
    <img src="/analysis/Fig1.png" width="720" height="432"
         alt="Bubble chart of ride summary data">
</figure> <br>

###  Analysis of total fare from Jan2019 to May2019 by city type 

- Tota fare is highest for urban cities and lowest for rural cities over time period.
- Total fare reamains relatively stable over the time period for all three city types.<br>

<figure>
    <figcaption>Total fare by city type over time period</figcaption>
    <img src="/analysis/PyBer_fare_summary.png" width="1440" height="432"
         alt="Total fare by city type over time period">
</figure> <br>

## Summary
- Total fares percentages by city types are 62.7% for urban, 30.5% for suburban and 6.8% for rural.
- Total rides percentages by city types are 68.4% for urban, 26.3% for suburban and 5.3% for rural.
- Total drivers percentages by city types are 80.9% for urban, 16.5% for suburban and 2.6% for rural.
- Driver count in urban cities is relatively high compared to rural and suburban cities. Driver count in urban cities may be balanced according to total rides. It might help to bring average fare per driver in line with that of rural and suburban cities.