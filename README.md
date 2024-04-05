# Formula 1 World Championship 2023
This article is part of the DADS5001 Data Analytics and Data Science Tools and Programming.
## Assignment
1. To create one chart (your selection) by using Plotly
2. Get your own data, clean, analyze, and plot
3. Link to yr Github (code)
   3.1 Post the image of your chart
   3.2 Explain your data sources
   3.3 Explain why choose the chart with your data

## About data set
data source : https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data
     The dataset consists of all information on the Formula 1 races, drivers, constructors, qualifying, circuits, lap times, pit stops, championships from 1950 till the latest 2023 season.
     In this study I choose only 2023 season to ananlyze.

## Average lap time of each Driver in every matches in 2023 season.
![newplot (1)](https://github.com/TripopN/data-visualization-with-plotly-express/assets/150440919/2321329e-d0b9-4560-9622-8790ddda9085)

   I choose 'lap_times' that contain number of lab and time of each lab in millisecond. merge with 'races1' table that contain all race in formation.
Each F1 race track is approximately 5-7 kilometers long. At each track, drivers drive an average distance of 300 kilometers.
   The graph above shows each driver's average driving time per lap (in seconds).To see how each driver performs in the 2023 race.
A low average lab time does not mean that a driver will be able to score well until the end of the season.It does mean that a driver is performing well overall for the season.
