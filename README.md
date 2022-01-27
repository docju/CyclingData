# Customer Usage of the San Francisco Bike Share scheme (SFMTA)
The San Francisco Municipal Transport Authority runs a bike share scheme, whereby customers can pick up aa bike at a station, ride to another station, and leave the bike in a new station for a one-off fee or a subscription for a given period.

This project seeks to answer some questions about usage and how the experience can be improved for users of the scheme.
> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
The project uses data taken from Kaggle from the first few months of 2019. It includes information on journeys including time taken, start and end points, whether the customer was a subscriber or a casual user, and the customer's gender. 

January data: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips?select=2019+-+01.csv
February data: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips?select=2019+-+02.csv
March data: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips?select=2019+-+03.csv
April data: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips?select=2019+-+04.csv
May data: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips?select=2019+-+05.csv

We can use this data to solve a number of problems and make inferences about customer usage to make the experience better for them. 

The main questions to be answered here are:

1) Which stations are susceptible to running out of available bikes, or not having room for customers arriving? If we know this, we can manage this by moving bikes from "fuller" ones to "empty" ones 
2) For the most popular start stations, what is the average travel time to other popular ending stations? This is information we could give the customer to allow them to plan ahead
3) Are there routes that are significantly more favoured by men than women? If so, this information could be used to investigate possible perceived issues with safety in the relevant areas


## Technologies Used
- Python - version 3.0
- Jupyter lab
- Microsoft Excel




## Usage
Download or link to the Cycling Data.ipynb file and run in a suitable environment such as Jupyter lab or Zeppelin. It requires no extra software.



## Project Status
Project is: Complete


## Room for Improvement

Room for improvement:
- Data does not include date time of day of the journey- this would enhance management of bikes in stations as well as weekday/ weekend trends
- I was not able to get the necessary packages to do a network map, so this would enhance the project somewhat




