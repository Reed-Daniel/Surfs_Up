# Surfs Up: Oahu
## Project Overview
After presenting our business case for a Surf'n'Shake shop in Oahu, our potential investor W. Avy would like more information on temperature trends in the area before committing to the investment. In this project we used SQLAlchemy to query our database of weather data and extract temperatures for the months of June and December in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
### June Temperature Statistics
<img width="126" alt="June_temps" src="https://user-images.githubusercontent.com/93271297/147995170-343d8be8-fdf4-4268-9513-c68c48bb263b.png">

### December Temperature Statistics
<img width="161" alt="Dec_Temps" src="https://user-images.githubusercontent.com/93271297/147995187-2fdd78b2-7189-4bb9-8de2-e0d81a718447.png">

1. December recorded the lowest temperature **(54&deg;F)** in comparison to June **(64&deg;F)**
2. June recorded the highest temperature **(85&deg;F)** although December had a similar high **(83&deg;F)** 
3. The average temperatures for both months were also similar **(June: 75&deg;F  --  December: 71&deg;F)**
4. Only **25%** of the temperatures recorded for December were below **69&deg;F** in comparison to June's **73&deg;F** first quartile temperature
5. Standard deviations for both months were low **(June: 3.25  --  December: 3.74)** 

## Summary
Judging from our data we can see that the average temperature in Oahu remains relatively similar during what would be the peak summer month (June) and peak winter month (December). Even though December recorded the lowest temperature, it's first quartile temperature **(69&deg;F)** tells us that the majority of the data stays at or above a reasonably warm temperature. The low standard deviations for both months also indicates that the temperatures generally do not stray too far away from warm average temperatures. Overall, the temperature data paints a positive picture for the sustainability of a surf and ice cream business year round. 

Additional queries on our weather database that could help support our findings include but are not limited to. 
- The precipitation statistics for each month to see how often rain was recorded as well as how much rain was recorded.
- Wind statistics for each month to see if there is a correlation between high/low winds and precipitation levels or surfing conditions
