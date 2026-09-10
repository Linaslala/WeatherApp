# WeatherApp

A weather app built with HTML, CSS and JavaScript. Search for any city to get the current weather, a 5-day forecast and weather icons.

## Tech stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
  - `async/await` with the Fetch API
  - DOM manipulation
- **OpenWeatherMap API** (current weather + 5-day forecast)

## Features

- Search by city (button or Enter key)
- Current temperature, condition, humidity and wind
- 5-day forecast with icons per condition
- Shows a "not found" state for unknown cities

## Getting started

```bash
git clone https://github.com/Linaslala/WeatherApp.git
cd WeatherApp
```

1. Copy `config.example.js` to `config.js`
2. Add your own OpenWeatherMap API key to `config.js` (register at [openweathermap.org](https://openweathermap.org/api))
3. Open `index.html` in your browser, or use VS Code's Live Server

> **Note:** The API key is no longer hardcoded. `config.js` is gitignored so the key is never committed. The `script.js` file reads the key from the `OPENWEATHER_API_KEY` global variable that `config.js` provides.

## Possible future improvements

- Move the API key out of the client code
- Add geolocation ("weather where I am")
- Add unit conversion (°C/°F)
- Add auto-complete for city names