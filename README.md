# Flatiron_Aviation_Report
## Project Background
### The primary business objective of this project is to make a recommendation to our client for which aircraft to purchase in order to minimize business risk. An additional area of analysis was to investigate which geographical areas were least risky to operate in.
### To answer these questions data from the National Travel Safety Board was processed and analyzed. This dataset included records for airplane accidents and incidents. One limitation of the data is that it did not include any information on the number of flights without accidents and incidents. Thus, the dataset is useful for understanding the accidents and incidents themselves, but not their rate of occurrence.¶

## Summary
### 1. First read in the data from the US National Travel Safety Board(NTSB) and saved it to dataframe
### 2. Reformatted dataframe columns to have _ instead of . for spaces
### 3. Reformatted aircraft companies that were duplicates
### 4. Used columns to filter out data:
### - filtered in investigations that had an aircraft category that was an airplane
### - filtered in investigations that were not amateurly built
### - filtered in investigations that happened after the year 2000
### - filtered in investigations that were either used in a commercial or private purpose
### 5. Formatted location data into state column, then formatted into a region column
### 6. Replaced nan data in injury columns to 0
### 7. Quantified impact to human safety and airplane damage by making new columns to track percentiles
### 8. Created two new data frames that seperately tracked top 20 counts of aircraft Makes by Commercial and Private aircrafts
### 9. Wrote the three dataframes to csv files Output_Data, Output_commercial, and Output_private
### 10. Appendix includes code that deals with investigations from 2001 to 2022 and investigation type from 2001 to 2022
## Presentation
### The Link to our presentation is [here](https://docs.google.com/presentation/d/1RquP1pQMuQ6j8GaRvvJ5-4ECo-hugXZX/edit?usp=sharing&ouid=101182939687611455982&rtpof=true&sd=true)

## Sources
### Data from the NTSB can be found [here](https://www.ntsb.gov/safety/data/Pages/Data_Stats.aspx)

## Navigation
### The python file and tableau file are in the main folder of the respository. The csv files can be found by navigating to the data folder.

## Tableau Dashboard
### The Link to our tableau dashboard is [here](https://public.tableau.com/app/profile/jackson.robbins/viz/Aviation_Visualization/Map)
![damage_commercial](images/damage_com_graph.png) 
![injury_commercial](images/injury_com_graph.png) ![fatality_commercial](images/fatality_com_graph.png)
![damage_private](images/damage_pri_graph.png)
![injury_private](images/injury_pri_graph.png) ![injury_private](images/fatality_pri_graph.png)

## Conclusion
### Aviat Aircrafts would be the best commercial aircraft for less risk of death, injuries, and airplane damage , while Gulfstream Aircrafts would be the best private aircraft for the same reasons. We also found that building hubs in the South East and North West to and from would yield the the lowest number of accidents.