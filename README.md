# Capital-Bike-Share-Program


Overview

Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. Using these systems, people are able rent a bike from a one location and return it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world.
Data Fields

    datetime - hourly date + timestamp
    season - 1 = spring, 2 = summer, 3 = fall, 4 = winter
    holiday - whether the day is considered a holiday
    workingday - whether the day is neither a weekend nor holiday
    weather -
        1: Clear, Few clouds, Partly cloudy, Partly cloudy
        2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
        3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
        4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
    temp - temperature in Celsius
    atemp - "feels like" temperature in Celsius
    humidity - relative humidity
    windspeed - wind speed
    casual - number of non-registered user rentals initiated
    registered - number of registered user rentals initiated
    count - number of total rentals (Dependent Variable)



This notebook explains how we can go about explore and prepare data for model building.The notebook is structured in the following way

    About Dataset
    Data Summary
    Feature Engineering
    Missing Value Analysis
    Outlier Analysis
    Correlation Analysis
    Visualizing Distribution Of Data
    Visualizing Count Vs (Month,Season,Hour,Weekday,Usertype)
    Filling 0's In Windspeed Using Random Forest
    Linear Regression Model
    Regularization Models
    Ensemble Models

Note:- Open the python file in google colab to view graphs and EDA