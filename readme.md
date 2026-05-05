# Climatrix — Smart Weather Web App

Climatrix is a modern, responsive weather application that provides real-time weather updates, location-based forecasts, and a clean, dynamic user interface. It leverages the OpenWeather API to deliver accurate weather data with an enhanced user experience.

---

## Features

### Real-Time Weather Search
- Search weather by city name
- Displays:
  - Temperature (°C)
  - Weather condition (description)
  - City name

### Geolocation Support
- Fetches weather using your current location
- Uses browser Geolocation API

### 5-Day Forecast
- Displays upcoming weather trends
- Shows daily temperature and weather icons

### Dynamic Weather Icons
- Uses OpenWeather icon set
- Changes based on current weather conditions

### Dynamic Background UI
- Background changes based on weather:
  - Sunny
  - Cloudy
  - Rainy
  - Snowy

### Smooth UX Enhancements
- Loading indicator while fetching data
- Error handling (invalid city, API issues)
- Enter key support for search
- Responsive and modern glassmorphism UI

---

## Tech Stack

| Technology | Usage |
|----------|------|
| HTML5 | Structure of the application |
| CSS3 | Styling, animations, glassmorphism UI |
| JavaScript (ES6) | Logic, API calls, DOM manipulation |
| OpenWeather API | Weather and forecast data |
| Geolocation API | User location detection |

---

## API Integration

Climatrix uses the **OpenWeather API** to fetch weather data.

### Current Weather Endpoint
```bash
https://api.openweathermap.org/data/2.5/weather?q={city}&units=metric&appid={API_KEY}