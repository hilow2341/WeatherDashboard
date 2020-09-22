# Weather Dashboard

## Description

A weather dashboard which displays the current weather and forecast for a searched city. Users can search for a city, and if found the app will return the current weather, as well as a forecast of the next 5 days. The user's search history is saved as a button for them to quickly check the weather of that city again. It uses the OpenWeather API to retrieve data for the cities, AJAX to hook into the API to retrieve the data in JSON format, dynamically updated HTML and CSS powered by jQuery, and displays a search history which the user can click to access past cities searched via local storage. 

## Approach
I started by dividing the main task into smaller tasks, as outlined below:
1. Get the user input city
2. Send the request to the Openweather server and retrieve the current weather and forecast
3. Show the information on screen