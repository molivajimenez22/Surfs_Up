# Surfs_Up
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/tatonomusic-FFCgotROOTY-unsplash.jpg">


## Overview of Analysis
W. Avy is planning to open a surf and ice cream shop in Hawaii. This analaysis `measures` temperature trends for June and December to determine if the business is sustainabble year-round.
    
## Results

Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the `hawaii.sqlite` database to retrieve the temperatures for the month of June and December. Additionally, I converted the temperatures to a list and then created a DataFrame. 

### **June - Temperatures, List and DataFrame**
<p align="center" width="100%">
    <img width="80%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/June_Temperatures_Final.JPG">
    
### **December - Temperatures, List and DataFrame**
<p align="center" width="100%">
    <img width="80%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/December_Temperatures_Final.png">
    
Finally, I generated the summary statistics for June and December temperatured DataFrames. 
<p align="center" width="100%">
    <img width="44%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/Summary_Stats.png">

## Summary 
Overall, the data showed that the weather in June and December are relatively similar, although December's high temperature more closely align with June's lower temperatures. 
    1. June mean = 75°F vs. December mean = 71°F
    2. December's temperature range is larger (56 to 83) to June's range (64 to 85)
    
Additional queries that could provide further details include:
    1. Using matplot to add a trendline for June/December precipitationn and temperatures
    2. Convert to list and generate summary statistics for June/December precipitation
