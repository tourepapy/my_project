# Capstone Applied Data Science Machine Learning Project Forecasting Sharing Bike Rental Demand: A Machine Learning Approach

## Problem Statement
The main objective of the Bike Sharing demand prediction project is to develop a machine learning model capable of accurately forecasting the number of bike rentals at different times of the day, given a set of features such as weather conditions, time, day of the week, and season. The aim is to enable Bike Sharing companies to optimize their operations, ensuring that bikes are available when and where they are needed, thereby improving customer satisfaction and operational efficiency.
http://capitalbikeshare.com/system-data 
http://www.freemeteo.com

## Background
Bicycle-sharing programs have emerged as a modern evolution of conventional bike rental services, offering an automated approach to the entire process encompassing membership registration, bicycle rental, and return. Users can conveniently pick up a bicycle from one location and return it to a different one. Presently, there are approximately 500 such programs globally, boasting a fleet of over 500,000 bicycles. These systems have garnered significant attention due to their substantial impact on urban transportation, environmental sustainability, and public health.

Beyond their practical urban applications, bicycle-sharing systems present intriguing opportunities for research due to the unique nature of the data they generate. Unlike other forms of public transportation such as buses or subways, these systems meticulously log each trip’s duration, starting point, and destination. This capability transforms bicycle-sharing networks into a de facto virtual sensor grid, poised to capture urban mobility trends. Consequently, it is anticipated that these systems could play a crucial role in identifying and understanding major urban events through continuous data monitoring.

## Data Description
Both hour.csv and day.csv have the following field, except hr which is not available in day.csv.
  - instant: record index.
  - dteday: date.
  - season: season (1: springer, 2: summer, 3: fall, 4: winter).
  - yr: year (0: 2011, 1:2012).
  - mnth: month (1 to 12).
  - hr: hour (0 to 23).
  - holiday: weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule).
  - weekday: day of the week.
  - workingday: if the day is neither weekend nor holiday is 1, otherwise is 0.
  - weathersit: 1- Clear, Few clouds, Partly cloudy, Partly cloudy
                    2- Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
                   3- Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain +   
                       Scattered clouds
                   4- Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
  - temp: Normalized temperature in Celsius. The values are divided to 41 (max).
  - atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max).
  - hum: Normalized humidity. The values are divided to 100 (max).
  - windspeed: Normalized wind speed. The values are divided to 67 (max).
  - casual: count of casual users.
  - registered: count of registered users.
  - cnt: count of total rental bikes including both casual and registered.

