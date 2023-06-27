# five-day-weather-forecast 

weather dashboard that runs in the browser featuring dynamically updated HTML and CSS

## Overview

HTML file links to bootstrap which provides the styling.  Javascript calls api from openweathermap.org then dynamically creates the card divs with attributes to display the current weather as well as the next five days.  When user types city name in the search input, the weather details are displayed; current conditions are prominent and the next five days are displayed below.  User searches are saved to local storage and dynamically created buttons make a list of buttons for user to click again for forecast.

Day.js was used to manipulate the api data to display the five days in the future and the appropriate plugins and syntax were used per the documentation.  Similarly, documentation in Bootstrap helped choose attributes and ids for elements.

## Approach

First thing was to establish the api data call and make sure it was coming over.  This required registering on openweathermap.org to request and api key.  To do this, the fetch/response/json function was used in JavaScript followed by a console.log to test it.   After that, minimal html structure was created in anticipation of dynamically creating more elements with styling to display the data.  An empty array was created to hold the json data as a string to use in the later functions.

Bootstrap and Day.js documentation provided the guidance on creating the displayed data. The weather api provided the data based on the geographic coordinates.  So an additional api link and additional function was necessary to return the data.

Lastly, the user search history needed a function for the user to click on their recent searches and simulate a new search for that city.

## Resources

 - The best resource was watching previous class recordings covering this topic.
 - The book "JavaScript The Comprehensive Guide" by Phillip Ackermann, chapters 9 and 12 also helped as a reference for dynamically creating elements and attributes as well as working with the api.
 - Documentation for Bootstrap and Day.js was essential. 

 ## Screenshot and Link
https://user-images.githubusercontent.com/128503077/249266699-cc41b491-e08c-466d-95a9-d4ed479d314a.png

https://github.com/aliehs111/weather-forecast/deployments/activity_log?environment=github-pages

