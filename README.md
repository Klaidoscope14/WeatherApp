# Weather App

This Weather App is a simple web application that allows users to check the current weather of any city. It fetches real-time weather data using the OpenWeatherMap API and displays it in an intuitive and visually appealing format.

## Features
- Search for the current weather by city name.
- Displays:
  - City name
  - Temperature in Celsius
  - Weather condition (e.g., cloudy, sunny, etc.)
  - Weather icon for better visualization
- Interactive and responsive user interface.

## Technologies Used
- **HTML5**: Structure of the application.
- **CSS3**: Styling and layout.
- **JavaScript (ES6)**: Client-side scripting and API interaction.

## Prerequisites
To run this app, you need:
1. A modern web browser (Chrome, Firefox, Safari, etc.).
2. An active internet connection to fetch real-time weather data.

## Setup Instructions
1. Clone or download the `WeatherApp.html` file to your local machine.
2. Open the file in any web browser.
3. Enter the name of the city in the input box and click the "Get Weather" button to view the weather information.

## How It Works
1. The user enters a city name and clicks the "Get Weather" button.
2. The app sends a request to the OpenWeatherMap API to fetch the weather data for the entered city.
3. If the city is found, the app displays the weather information. Otherwise, an error message is shown.

## API Integration
This app uses the OpenWeatherMap API to retrieve real-time weather data. It requires an API key, which is included in the code:

```javascript
const response = await fetch(
  `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=71bbda42ee25f37270d7987198732394`
);
```

> Note: Replace the placeholder API key with your own API key if you encounter any issues or wish to use a different account.

## Styling
The app has a clean and modern design featuring:
- A gradient background.
- Rounded input and button elements.
- A weather information display styled with CSS to ensure readability.

## Limitations
- The app depends on the OpenWeatherMap API and requires an active API key.
- The app only supports fetching weather data by city name.
- Internet connectivity is required.

## Future Enhancements
- Add support for fetching weather data based on the user's current location.
- Display additional weather details such as humidity, wind speed, and forecast.
- Improve error handling for invalid or incomplete inputs.

## License
This project is open-source and available for use under the MIT License. Feel free to contribute or modify the code as needed.
