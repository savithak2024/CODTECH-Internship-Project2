Name : Savitha k
Company : CODTECH IT SOLUTIONS
ID : CT04DS7522
Domain : Web development
Duration : 25th August 2024 To 25th september 2024


Overview
The provided code is for a Weather App that allows users to search for real-time weather data by entering a city name. The app displays information such as temperature, weather conditions, humidity, and wind speed. If the user inputs an invalid city name, an error message is displayed.

Key Activities
City Search Input: Users can type in the name of a city in an input field. Upon clicking the search button, the app fetches weather data for that city using an API request.
Fetching Weather Data: The app uses the OpenWeatherMap API to get the weather data. The inputted city name is passed to the API, which returns data such as temperature, humidity, wind speed, and current weather conditions.
Displaying Weather Data: If a valid city is found, the weather data is displayed on the screen. It includes:
Temperature
City name
Weather conditions (like rain, clouds, drizzle, mist, etc.)
Humidity percentage
Wind speed
The app also updates the weather icon dynamically based on the current weather condition.
Handling Errors: If the city name is invalid or not found in the OpenWeatherMap API, an error message is displayed, and the weather data is hidden.

Technologies Used
HTML:
Defines the structure of the web app, including the search input field, weather data display, and error messages.
CSS:
Styling and Layout: The app's appearance is designed with a gradient background and centered card layout for the weather data.
Flexbox: Used to align and arrange elements such as the search bar, weather details (humidity, wind speed), and weather icons.
JavaScript:
API Fetching: Uses the fetch() method to make an asynchronous HTTP request to the OpenWeatherMap API and retrieves real-time weather data.
Event Handling: Listens for a click event on the search button, then processes the user's input and triggers the weather data fetch.
Dynamic Content: Updates the DOM dynamically based on the fetched weather data and changes the content of elements (city name, temperature, icons) accordingly.
Error Handling: Displays an error message if the API returns a 404 status (city not found).
OpenWeatherMap API:
A weather service API that provides real-time weather information based on the city name. The API returns various weather data in JSON format, which the app processes and displays.
