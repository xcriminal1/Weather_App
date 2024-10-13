## Link
https://xcriminal1.github.io/Weather_App/

# Weather App with Dynamic Background

This is a simple weather application that dynamically updates the background image based on the current weather conditions at the user's location. The app uses HTML, CSS, JavaScript, and the OpenWeather API to fetch weather data and the Unsplash API to change the background image.

## Features

- Fetches user's location (latitude and longitude) using the browser's Geolocation API.
- Displays current weather information including temperature, weather description, and city name.
- Changes the background image dynamically based on the weather condition (e.g., sunny, rainy, cloudy) using the Unsplash API.
- Smooth transition between background images for an enhanced user experience.

## Technologies Used

- HTML5
- CSS3 (for styling and animations)
- JavaScript (for handling geolocation, API calls, and DOM manipulation)
- [OpenWeather API](https://openweathermap.org/api) (for fetching weather data)
- [Unsplash API](https://unsplash.com/developers) (for fetching weather-related background images)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- A modern web browser that supports the Geolocation API.
- Access to the internet to fetch weather data and images.
- API keys from both OpenWeather and Unsplash. You can register for free keys at:
  - [OpenWeather API](https://openweathermap.org/api)
  - [Unsplash Developer](https://unsplash.com/developers)

## How It Works

1. The app uses the browser's Geolocation API to get the user's current latitude and longitude.
2. The latitude and longitude are sent to the OpenWeather API to fetch the weather details (temperature, weather condition, etc.).
3. Based on the weather condition (e.g., "Clear", "Clouds", "Rain"), a relevant background image is fetched from the Unsplash API.
4. The app displays the current weather information along with a background image that matches the weather condition.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app-dynamic-background.git
   cd weather-app-dynamic-background
   ```

2. Get your API keys:
   - Sign up for the [OpenWeather API](https://openweathermap.org/api) to get your API key.
   - Sign up at [Unsplash Developer](https://unsplash.com/developers) and create a new app to get your Unsplash API key.

3. Add your API keys to the JavaScript file:
   Open the `script.js` file and replace the placeholders with your actual API keys:
   ```javascript
   const weatherApiKey = 'YOUR_OPENWEATHER_API_KEY';
   const unsplashApiKey = 'YOUR_UNSPLASH_API_KEY';
   ```

4. Open the `index.html` file in your browser to run the app.

## Usage

1. Once the app is running, it will automatically ask for permission to access your location.
2. After granting permission, the app will display the current weather based on your location and change the background image accordingly.
3. You can refresh the page to see updated weather information and a new background image.


## Future Enhancements

- Add more detailed weather information (humidity, wind speed, etc.).
- Include a search feature to allow users to check the weather for other locations.
- Implement a dark mode option for better usability in low-light environments.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
