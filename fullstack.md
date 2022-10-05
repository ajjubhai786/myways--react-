# Fullstack Test
An MERN stack focused take home test for Fullstack Developers.

## Instructions
+ Clone this repo
+ Complete this exercise and submit either a zip of the solution or a link to a new repo
+ Please use MERN stack to build this. All other choices of libraries, frameworks, etc. are up to you.

## Requirements
+ Create a dropdown that searches for Cities using this [API](https://open-meteo.com/en/docs/geocoding-api)
  + Sample API URL for New York: https://geocoding-api.open-meteo.com/v1/search?name=new%20york
+ Once an option is selected, open a new page for the selected city and load the weather date for that city using this [API](https://open-meteo.com/en/docs)
  + Sample API URL for New York: https://api.open-meteo.com/v1/forecast?latitude=40.71427&longitude=-74.00597&current_weather=true&timezone=auto&daily=sunrise,sunset,apparent_temperature_max,apparent_temperature_min
+ Solution should be similar to [this](https://weather.com/en-IN/weather/today/l/96f2f84af9a5f5d452eb0574d4e4d8a840c71b05e22264ebdc0056433a642c84)
+ Show the "current" conditions for the selected city, say, New York:
  + Location (ie. New York, NY, USA)
  + Current temperature
  + Today's high temperature
  + Today's low temperature
  + A Line Chart to display sunrise and sunset data (both within same chart)
+ Create a backend server to build and save:
  + User signups
  + Wishlist cities (after login/signup)
  + Recent search data (after login/signup)
+ Based on login/signup status the dashboard should behave like this:
  + Dropdown search box at all times at the top
  + If user is authenticated:
    + Show recent searches below the dropdown, clickable and same behaviour as dropdown's, if available
    + Show wishlisted cities below the recent searches, clickable and same behaviour as dropdown's, if available
