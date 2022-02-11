# OpenWeatherMap_Challenge

## Purpose
Utilize API's to create databases, extract weather data, and forumulate vacation plans.

## Results 

There are three deliverables with respect to this project:

1. First, the random function from NumPy was used to generate a set of 2,000 random latitudes and longitudes. Another function import was made for CitiPy to retrieve the nearest city from the afforementioned coordinates, and perform an API call with the OpenWeatherMap. In addition to the city weather data gathered, the dataframes were assessed further to retrieve the current weather description for each city. At the end, a new DataFrame containing the updated weather data was provided and exported for vacation planning purposes.

2. The second deliverable allows the user to input criteria statements to retrieve customer weather preferences. Based on a temperature range of 75 to 90 degrees Fahrenheit , those preferences were used to identify potential travel destinations and nearby hotels. Last, the information for those destinations were displayed on a marker layer map with pop-up markers.

3. The third deliverable utilizes the Google Directions API to create a travel itinerary that shows the route between four cities chosen at random, within the same country, from all the customer’s possible travel destinations created in the second deliverable. Then, a marker layer map with a pop-up marker for each city on the itinerary and it's associated weather information is provided.