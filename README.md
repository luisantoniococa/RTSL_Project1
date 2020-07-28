# Flight Delay MCI Airport 2019

## Motivation and Process

+ Analyzed flight data for 2019 to date to find trends and/or correlations among factors such as carrier delays, days of the week, and cancellations for better and informed decisions to travel to and from Kansas City.
+ Motivation: We were thinkin of vacation and how nice it would be as we ruminate over our project. 
+ Process: Started big and pared it down.
   + It began with pricing, best day of week on flights, hotels, attractions, transportation, etc.
   + This was too much information to analyze with the time that we had, so we started asking questions based off our data source.
   + We narrowed down our questions to flight delays in airport. This would be helpful for someone that would like the least amount of time waiting in an airport.


## Questions and Summary
The goal of this project was to be able to answer some of the following questions with data.

### Questions:
- Do any airline carriers have more delays than others?
- What is the best day of the week for travel to avoid delays?
- What are the regions and months with the most weather delays?
- What are the best airlines regarding cancellations?
### Summary:
- There were some obvious issues with delays for a couple of specific airlines. 
- Overall, the average delay time is within a few minutes for each day of the week, whether due to weather, carrier, security or any other purpose.
- We can identify trends based in the amount of weather delays by region 
- Looking at data there is no big variance in the percentage of flights getting cancelled




This project takes Data from the Bareu of Transportations, then focus in airlines and how much delay is expected from diferent airlines.

A more detailed explanations can be found in the project report at the following link.


https://docs.google.com/presentation/d/1GsJAR0b5-oG4VeoJQ21Qd6NHZZt3nkufLmy6z7jVR38/edit?usp=sharing

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
# We need to get the following packages in addition to Python 3.6 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import requests

```

### Installing

In order for make sure to have the following libraries installed.

```
pip install numpy
pip install pandas
pip install matplotlib
pip install request
# also we can replace pip install for pip3 depending if there is more versions of Python 
```

### Background
The Bareu of Transportations has a very large datasets for aviation comercial and prvate. Based in this information we finded different insights in wich airlines delays are the ones that take longer based in how much delay time from the airline.
When looking at this dataset we can observe that it does a great job at separating the different reasons for delaying, by separatig them in sections. 
Some of them include, airport delay, weather delay, traffic control delay and others. 
