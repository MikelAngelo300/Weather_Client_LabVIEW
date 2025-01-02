# Weather Station VI

This project is a LabVIEW Virtual Instrument (VI) that retrieves real-time weather data from the OpenWeatherMap API and displays it in a user-friendly graphical interface. It provides detailed information about the weather conditions in any selected city.

## Features

- City Selection: Enter the name of a city to view its weather data.
- Weather Details:
  - Current temperature, "feels like" temperature, maximum and minimum temperatures.
  - Humidity percentage visualized with a humidity meter.
  - Wind speed and direction displayed with a gauge and compass.
  - Visibility, atmospheric pressure, and cloud coverage.
  - Sunrise and sunset times, along with the current time and date.
- Temperature Units: Toggle between Celsius, Fahrenheit, and Kelvin.
- Graphical Elements: Thermometer, humidity meter, wind speed gauge, and wind direction compass for intuitive visualization.

## Requirements

- LabVIEW installed on your computer.
- An active internet connection.
- API key from OpenWeatherMap (sign up at https://openweathermap.org/).

## How to Use

1. Setup:
   - Obtain an API key from OpenWeatherMap.
   - Integrate the API key into the VI (refer to the code or block diagram for the appropriate location).
2. Run the VI:
   - Open the `stacja_pogodowa.vi` file in LabVIEW.
   - Enter the city name and select the desired unit of temperature.
   - Click the start button to fetch and display weather data.
3. View Data:
   - Explore various weather parameters displayed on the interface.

## Notes

- Ensure that the city name is correctly spelled for accurate results.
- The VI handles basic errors, but additional error-handling features can be implemented.
- API calls are limited based on your OpenWeatherMap plan.

## License

This project is for educational purposes and is free to use and modify. Please credit the original creator if shared or published.

