# Weather_Dashboard
Creating a weather dashboard to display the weather in multiple cities 

1. Started by getting a connection between the openweather using an API key in order to retrieve the data needed in order to display the weather on the HTML page.
2. Used console log in order to find where each piece of information needed to display was in the weather object.
3. Created variables for each of the city, temp, humidity, and windspeed
4. Created a variable called “cities” that held an array of the different cities that would be used for the dashboard.
5. Ran the Ajax call to the open weather app in order to get the data for dashboard.
6. Created a variable that would convert the kelvin temperature into fahrenheit 
7. Created a div called “City Div” which would hold all the buttons for the cities and data from open weather 
8. Created variables for the City, Temperature, Wind and Humidity and using JQuery created new divs to be assigned to these variables 
9. Appended all the data variables to their created divs and then appended them all to the “City Div”
10. Created a for loop that ran the cities variable through it and created buttons for each of the cities that were in the “cities” array.
11. Added a click function for when people add a city into the text area they could add a button and then run a search in order to find the current weather
12. Created a function that would run when any of the city buttons were click and would display the current weather data from the Ajax call for the specific city.
