# World_Weather_Analysis
Module 6
**Purpose**

The purpose of this challenge is to enhance the PlanMyTrip app by using weather description data retrieved during this module. Then, using that information, input potential preferences into the code and find travel destinations and nearby hotels. From the generated list of cities from the temperature preferences, we will select four cities and create a travel route using the Geoapify Routing API.

**Results** 

Using the code and API keys for Geoapify, we randomly generated 2,000 pairs of latitudes and longitudes and found the nearest cities using the citipy module. Then, using pandas dataframes and geoviews, we selected cities that met the weather conditions we set as parameters and displayed them on a map. We then found nearby hotels for those chosen cities and selected four random cities to create a drivable travel route, which we plotted on a map. 

**Analysis**

We have learnt how to use API keys to retrieve data from different sources and use that data to create maps and travel routes. We can use this information to help customers plan their trips and find the best travel destinations for them.