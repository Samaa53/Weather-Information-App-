# Weather Information App

## Overview

The Weather Information App is a Java-based application designed to provide real-time weather data. It uses the OpenWeatherMap API to fetch weather information and displays it through a graphical user interface (GUI) built with Java Swing. The app allows users to view temperature, humidity, wind speed, and weather conditions, with options for unit conversion and search history tracking.


## Features

- **Real-time Weather Data:** Fetch and display current temperature, humidity, wind speed, and weather conditions.
- **Unit Conversion:** Convert temperatures between Celsius and Fahrenheit and wind speeds between km/h and mph.
- **Weather History:** Maintain and display a history of previous searches.
- **Weather Icons:** Show weather condition icons fetched from OpenWeatherMap.
- **Forecast Display:** Change the GUI background color based on current weather conditions.

## Getting Started

### Prerequisites
Ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- Internet connection (for API access)

### Installation and Running the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/weatherapp.git

2. **Navigate to the Project Directory:**

   ```bash
   cd weatherapp

3. **Compile the Java Source Files:**

   ```bash
   javac -d bin src/weatherapp/*.java src/WeatherAppGUI.java src/WeatherAPI.java src/WeatherHistory.java src/WeatherIconManager.java

4. **Run the Application:**

   ```bash
   java -cp bin weatherapp.Main


  ## Usage
1. **Launch the Application:**
- Run the compiled Main class to open the Weather Information App GUI.

2. **Search for Weather:**
- Enter a location in the text field and click the "Search" button to fetch weather data.

3. **View Weather Data:**
- The application displays temperature, humidity, wind speed, and weather conditions.
- Select units (Celsius or Fahrenheit) from the dropdown menu to adjust the displayed values.

4. **View Forecast:**
- A mock 8-day forecast is displayed in the forecast area.

5. **View Search History:**
- The history panel shows a list of previous weather queries with timestamps.

6. **Change Background:**
- The background color of the GUI changes based on current weather conditions (e.g., clear sky, cloudy, rainy).

## Implementation Details
- **WeatherAPI.java:** Handles communication with the OpenWeatherMap API to fetch weather data.
- **UnitConverter.java:** Provides methods to convert temperature and wind speed units.
- **WeatherAppGUI.java:** Contains the GUI implementation using Swing, including user input handling and data display.
- **WeatherHistory.java:** Manages a history of weather queries.
- **WeatherIconManager.java:** Maps weather conditions to text-based symbols.

## Notes
- Ensure you have a valid OpenWeatherMap API key to fetch weather data. You can replace the API_KEY variable in WeatherAPI.java with your own key.
- The application requires an internet connection to fetch weather data.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- OpenWeatherMap API for weather data.
- Java Swing for building the graphical user interface.

## Code Structure

   ```bash
main/
└── java/
    └── Main.java
weatherapp/
├── UnitConverter.java
├── WeatherAPI.java
├── WeatherAppGUI.java
├── WeatherData.java
├── WeatherHistory.java
└── WeatherIconManager.java
