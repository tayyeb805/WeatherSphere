# WeatherSphere 🌤️

**WeatherSphere** is a clean and responsive web application that provides real-time weather updates and a 5-day forecast for any location. It uses the OpenWeatherMap API to fetch weather data based on city name or user’s current location.

## Features

- 🌍 Search weather by city name
- 📍 Get weather using your current location
- 🌡️ Toggle between Celsius and Fahrenheit
- 📅 View a 5-day weather forecast
- ⚙️ Displays humidity, wind speed, pressure, and more
- 🔁 Graceful fallback with sample data in case of errors

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- [OpenWeatherMap API](https://openweathermap.org/)

## Setup Instructions

1. Clone the repository or download the project files.
2. Place your OpenWeatherMap API key in the `script.js` file.
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```
3. Make sure the folder structure includes:
   ```
   ├── index.html
   ├── js/
   │   └── script.js
   ├── css/
   │   └── style.css
   └── images/
       └── favicon.ico
   ```
4. Open `index.html` in your browser.

## Deployment

This project is not hosted yet. You can deploy it using platforms like:
- GitHub Pages
- Netlify
- Vercel

## License

This project is open-source and free to use for educational or personal projects.

---

> Weather data provided by [OpenWeatherMap](https://openweathermap.org/)