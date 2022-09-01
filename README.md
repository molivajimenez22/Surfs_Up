# Surfs_Up
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/tatonomusic-FFCgotROOTY-unsplash.jpg">


## Overview of Analysis
W. Avy is planning to open a surf and ice cream shop in Hawaii. This analaysis `measures` temperature trends for June and December to determine if the business is sustainabble year-round.
    
## Results

**Deliverables**

1. Determine the Summary Statistics for June
2. Determine the Summary Statistics for December
3. Summary statistics for June and December
    
**Method for Summary Statistics**
    
1. Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the `Measurements` table in the `hawaii.sqlite` database to retrieve the temperatures for the month of June and December. 
2. Additionally, I converted the temperatures to a list and then created a DataFrame. 
3. Finally, I generated the summary statistics for June and December temperatures DataFrames. 
    
The snapshots below shows the output of the above.

### **1. Summary Statistics for June - Temperatures, List and DataFrame**

<p align="center" width="100%">
    <img width="80%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/June_Temperatures_Final.JPG">
    
### **2. Summary Statistics for December - Temperatures, List and DataFrame**
<p align="center" width="100%">
    <img width="80%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/December_Temperatures_Final.png">
    
### **3. Summary Statistics for June and December**
    
<p align="center" width="100%">
    <img width="44%" src="https://github.com/molivajimenez22/Surfs_Up/blob/main/Resources/Summary_Stats.png">
    
Three key differences in weather between June and December

1. The mean temperature for June is higher in June at 75°F than 71°F in December
2. December's temperature range is larger (56 to 83) to June's range (64 to 85)
3. June's standard deviation is smaller than December, which could mean that the temperatures in June are clustered around the mean

## Summary 
Overall, the data showed that the weather in June and December are relatively similar, although December's high temperature more closely align with June's lower temperatures. My recommendation is that further analysis be made. Additional queries that could provide further details include:
   
1. Using matplot to add a trendline for June/December precipitationn and temperatures
2. Convert to list and generate summary statistics for June/December precipitation
