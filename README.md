# weather-website

This project retrieves real-time weather information for a specified city using the OpenWeatherMap API. It displays temperature, humidity, and weather description for the entered city.

# Requirements
To run this project, you need Python and the following library:
requests

# Setup
Get an API Key: Sign up at OpenWeatherMap and obtain an API key.

Set API Key: Replace the placeholder in API_KEY with your actual OpenWeatherMap API key.

# How It Works
Build API Request: The script builds a request URL by combining the base URL, city name, API key, and units of measurement (metric or imperial).

Send Request: It sends a GET request to OpenWeatherMap to retrieve the weather data in JSON format.

Extract Data: The JSON response is parsed to extract:

Temperature (in Celsius by default)
Humidity percentage
Weather Description (e.g., clear sky, rain)
Display Data: The extracted information is printed in a readable format. If the city is not found, an error message is shown.

# Usage
Set the API Key: Replace the API_KEY variable with your OpenWeatherMap API key.

Run the Script: The script will prompt you to enter a city name, then display its current weather

