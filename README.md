# Weather App

## Overview

The Weather App is a simple web application that provides real-time weather information for any city entered by the user. It fetches data from the OpenWeatherMap API and displays the current temperature, humidity, wind speed, and an appropriate weather icon based on the weather condition.

## Features

- **Search Functionality**: Users can search for the current weather in any city by entering the city name.
- **Real-Time Weather Data**: Fetches and displays real-time weather data including temperature, humidity, and wind speed.
- **Weather Icons**: Displays different weather icons based on the current weather conditions (e.g., clear, clouds, rain, drizzle, mist).
- **Error Handling**: Displays an error message if an invalid city name is entered.

## Technologies Used

- **HTML**: For structuring the content of the web application.
- **CSS**: For styling the web application to make it visually appealing.
- **JavaScript**: For fetching weather data from the OpenWeatherMap API and updating the DOM with the fetched data.
- **OpenWeatherMap API**: For retrieving current weather data.

## Project Structure

/weather-app
├── index.html          # The main HTML file  <br>
├── style.css           # The CSS file for styling  <br>
├── index.js            # The JavaScript file for API calls and DOM manipulation  <br>
└── images/             # Folder containing weather icons and search icon  <br>
    ├── search.png  <br>
    ├── clouds.png  <br>
    ├── clear.png  <br>
    ├── rain.png  <br>
    ├── drizzle.png  <br>
    ├── mist.png  <br>
    ├── humidity.png  <br>
    └── wind.png  <br>


## How to Use

1. **Open the App**: Open `index.html` in a web browser.
2. **Enter City Name**: In the search box, type the name of the city for which you want to know the weather.
3. **Click Search**: Click the search button (magnifying glass icon).
4. **View Weather**: The app will display the current temperature, humidity, wind speed, and a weather icon corresponding to the weather condition of the entered city. If the city name is invalid, an error message will be shown.

## Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Open `index.html`**: Open the `index.html` file in your preferred web browser.

## API Key

The app uses the OpenWeatherMap API to fetch weather data. You need an API key to use this service.

- You can get your API key by signing up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

- Replace the `apiKey` value in `index.js` with your own API key:
    ```javascript
    const apiKey = 'your_api_key_here';
    ```

## CSS Styling

The application uses a combination of Flexbox for layout and linear gradients for background styling to create a visually appealing user interface. Custom weather icons are used to visually represent different weather conditions.

## Error Handling

- If the user enters an invalid city name, an error message ("Invalid city name") is displayed.
- The error message is hidden when valid weather data is retrieved.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize and enhance the Weather App as per your requirements. Happy coding!

