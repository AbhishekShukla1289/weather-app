# Weather App

A simple weather application built with HTML, CSS, and JavaScript that allows users to search for the current weather in any city using the OpenWeatherMap API.

## Features
- Search for weather by city name
- Displays temperature, humidity, wind speed, and weather condition
- Shows weather icons for different conditions (clouds, rain, snow, etc.)
- Handles invalid or empty city names with user-friendly error messages

## Screenshots
![Weather App Screenshot](images/clouds.png)

## Getting Started

### Prerequisites
- A modern web browser
- Internet connection (to fetch weather data from the API)

### Installation
1. Clone or download this repository to your local machine.
2. Open `index.html` in your web browser.

### Usage
1. Enter the name of a city in the search box.
2. Click the search button.
3. View the current weather information for the entered city.

## API
This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You can use your own API key by replacing the value of `apiKey` in the JavaScript section of `index.html`.

## Project Structure
```
weather-app/
  index.html
  styles.css
  images/
    clear.png
    clouds.png
    drizzle.png
    humidity.png
    mist.png
    rain.png
    search.png
    snow.png
    wind.png
```

## License
This project is licensed under the MIT License.