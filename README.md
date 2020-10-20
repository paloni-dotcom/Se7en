# Se7en

![NY plate](https://github.com/paloni-dotcom/Se7en/blob/main/Images/renew_registration_hero.jpg?raw=true)

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Project Proposal: How is the car you drive affecting the air quality and weather in your neighborhood?

Notes: Limiting our sample to New York State

### Data Source:
Main source of data is from https://data.ny.gov/Transportation/Vehicle-Snowmobile-and-Boat- Registrations/w4pv-hbkt
We will also be using Census data: https://www.census.gov/data.html 

### Preview of the vehicle data set:

![alt text](https://github.com/paloni-dotcom/Se7en/blob/main/Images/sampletabledata.png)

The data set has over 11 million rows and includes the following information:
Record Type, Vin, Registration Class, City, State, Zip, County, Model Year, Make, Body Type, Fuel Type, Unladen Weight, Maximum Gross weight, Passengers, Reg Valid Date, Reg Expiration Date, Color, Scofflaw Indicator, Suspension Indicator, Revocation Indicator.
There are 4 types of records: Boat, Snowmobile, Trailer and Vehicle.
This data will be pared down to private vehicles in NY State with an unexpired registration.
    
We plan to collect the following data using the APIs provided:
Record Type, Registration Class, City, Zip, County, Model Year, Make, Body Type, Fuel Type, Reg Valid Date, Reg Expiration Date, Color
Registration Class: PAS and SRF (passenger vehicles)


### Questions to ask/Tasks to do:
* Distribution of cars across the state compared to air quality. Data sets Vehicle distribution in New York State (https://data.ny.gov/Transportation/Vehicle-Snowmobile-and-Boat-Registrations/w4pv-hbkt) and Air Quality data (https://docs.airnowapi.org/HistoricalObservationsByZip/docs)
You can find the air quality index here: https://docs.airnowapi.org/docs/AirNowAPIFactSheet.pdf
This part can be divided into 2 parts: Finding the number of vehicles by zipcode and finding the air quality index(AQI) by zipcode. And plotting a heat map showing the air quality index and number of cars
* Same as above but compare age of cars with air quality data.
* Same as above but check if electric/hybrid vehicles had any effect on air quality
* Checking if the increase in cars affected the weather. We look at the Vehicle data set and check the vehicle model year and graph the average max and min temp over the years along with the number of cars by model year. Here we will assume the car was purchased during the model year.
* Statistical tables. Have to figure this one. What statistics can we look for.


### Questions:
* Distribution of Electric cars across the state with regard to Urban (Suburban) vs Rural
    ownership.
* Age of vehicles across the state.
* Vehicle ownership across the state compared to population(or median income).
* Most popular make and color.
* Comparison of electric cars vs non-electric.

### APIs:
* https://dev.socrata.com/foundry/data.ny.gov/w4pv-hbkt : used to retrieve the vehicle data
* Air Quality API from AirNow
*  Open Weather API
* Google Maps API

    


## Screenshots
![Example screenshot](./img/screenshot.png)

## Technologies
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Setup
Required dependencies:

pip install pandas
pip install sodapy

## Code Examples
Show examples of usage:
`put-your-code-here`

## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3


## Status
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Inspiration
Add here credits. Project inspired by..., based on...

## Contact
Created by 
[@celeste1030](https://github.com/) 
[@deepavadakan](https://github.com/) 
[@paloni-dotcom](https://github.com/) 
[@timsamson](https://github.com/) 
[@williamrosen](https://github.com/) 