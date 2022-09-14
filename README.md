# Project Name
Bike Sharing
Multiple linear regression model for the prediction of demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Data Description: The Data contains the count of total rental bikes including both casual and registered in the years 2018 and 2019. Along with the date & time, weekday/working day/holiday data; and climatic data are provided.


## Conclusions
The bike sharing cnt is dependent on the season, feeling temperature, yr and weather situation.

The bike sharing `cnt` is dependent on the season, feeling temperature, yr and weather situation.
- Year on Year the bike sharing `cnt` is increasing. In 2020, the bike sharing `cnt` is expected to increase from 2019
- During off-season (spring season) the bike sharing `cnt` is relatively less. 
	Suggestion: An off-season discount on bike sharing might increase the bike sharing `cnt` in spring season
- `atemp` the feeling temperature potentially includes the `humidity` and the `windspeed`. When the feeling temperature is favourable, the bike sharing `cnt` is increasing
- However, irrespective of the `atemp`, `yr` and `season`, if there is a possibility of Rain or Snow, the bike sharing `cnt` is reduced. When the `weathersit` shows a ckear sky or no Rain/Snow, the bike sharing `cnt` is increasing. 


## Technologies Used
# Linear algebra & data processing
numpy	
pandas
# Scientific and technical computing
scipy
# Estimate statistical models, and perform statistical tests
statsmodels 
# Visualization
matplotlib 
plotly
seaborn


## Acknowledgements
IIIT-B & Upgrad Study Materials


## Contact
Created by [@elcommselva] - feel free to contact me!
