# Se7en

Project Proposal: Distribution of Vehicles in the State of New York


The aim of this proposal is to look at the distribution of vehicles across New York State (for car dealers to optimize their inventory). We will look at distribution of Electric cars, age of vehicles across the state, average number of vehicles by population and most popular make and color.

Data Source:
Main source of data is from https://data.ny.gov/Transportation/Vehicle-Snowmobile-and-Boat- Registrations/w4pv-hbkt
We will also be using Census data: https://www.census.gov/data.html 

Preview of the vehicle data set:

https://github.com/paloni-dotcom/Se7en/blob/main/Images/sampletabledata.png

The data set has over 11 million rows and includes the following information:
Record Type, Vin, Registration Class, City, State, Zip, County, Model Year, Make, Body Type, Fuel Type, Unladen Weight, Maximum Gross weight, Passengers, Reg Valid Date, Reg Expiration Date, Color, Scofflaw Indicator, Suspension Indicator, Revocation Indicator.
There are 4 types of records: Boat, Snowmobile, Trailer and Vehicle.
This data will be pared down to private vehicles in NY State with an unexpired registration.
    
We plan to collect the following data using the APIs provided:
Record Type, Registration Class, City, Zip, County, Model Year, Make, Body Type, Fuel Type, Reg Valid Date, Reg Expiration Date, Color
Registration Class: PAS and SRF (passenger vehicles)

Questions:
1. Distribution of Electric cars across the state with regard to Urban (Suburban) vs Rural
ownership.
2. Age of vehicles across the state.
3. Vehicle ownership across the state compared to population(or median income).
4. Most popular make and color.
5. Comparison of electric cars vs non-electric.

APIs:
1. https://dev.socrata.com/foundry/data.ny.gov/w4pv-hbkt : used to retrieve the vehicle data
2. Census API : to retrieve population data for New York State
3. Google Maps API