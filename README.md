# US-Airline-KeyLocation-CarbonEmission-Profitable-Routes-Operations
cKDTree and Folium

# Problem Statement
  To determine high-score cities based on population density and airport proximity scores, and calculating CO2 emissions for valid points to assess the environmental impact of airline operations using Python.

# Datasets
* US_City
* Airport

# Methods and Flow used
1) scipy.spatial.cKDTree for efficient nearest neighbor searches
2) Calculate a score for each city based on population and airport proximity [population /density]
3) Filter out cities with a high score, indicating high population density  
   Calculate the 90th percentile of the 'Score' column i.e. to find the value below which 90% of the data falls [score > 0.9 quantile]
4) Folium used for interactive maps to mark high score citys
5) Co2 Emission calculation    [ Assuming emission rate is 150g/km as given in the Project slide]
   co2_emission = distance_km * 150
   

