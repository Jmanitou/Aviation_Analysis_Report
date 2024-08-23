# Flatiron_Aviation_Report
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