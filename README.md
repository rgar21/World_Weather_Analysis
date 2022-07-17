# World_Weather_Analysis

Using Jupyter Notebook along with OpenWeatherMap and GoogleMaps API to compile destination data. 

## Purpose

The purpose of this project is to provide our client with a solution to create maps based on desired weather parameters for customer vacation planning. Through the use of APIs from OpenWeatherMap and GoogleMaps we were able to provide destination hotel accomodations based on the search parameters from customer input.

## Overview 

In order to provide our customers with some possible destinations we began by compiling a list of 2000 random latitudes and longitudes. Using our citipy module we took these latitudes and longitudes and retrieved the nearest city to these coordinatres. We then used our OpenWeather API to pull current data on the weather parameters for each city that could then be used to filter our customers destinations based on the desired conditions. Finally, we created a code that can use GoogleMaps API to find accomodations for each desired destination and display a map with several key metrics such as hotel name, city, country and current weather. 

