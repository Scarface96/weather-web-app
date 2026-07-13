# Weather Web App

A real-time weather application displaying current conditions, forecasts, and weather information.

## 📋 Overview

A responsive weather application built with HTML, CSS, and JavaScript that provides current weather data and forecasts for any location.

## 🌤️ Features

- **Current Weather** – Temperature, conditions, humidity, wind
- **Location Search** – Look up weather for any city
- **Geolocation** – Auto-detect location
- **Forecast** – 5-day or extended forecast
- **Weather Icons** – Visual weather indicators
- **Temperature Units** – Switch between Celsius/Fahrenheit
- **Responsive Design** – Works on all devices
- **Weather Alerts** – Severe weather notifications

## 🛠️ Technologies Used

- **HTML5** – Markup
- **CSS3** – Styling and animations
- **JavaScript (Vanilla)** – Logic and API calls
- **Weather API** – OpenWeatherMap or similar
- **Fetch API** – Data retrieval

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Weather API key (OpenWeatherMap, etc.)

### Installation

```bash
# Clone the repository
git clone https://github.com/Scarface96/weather-web-app.git
cd weather-web-app

# Open in browser
open index.html  # macOS
# or
start index.html  # Windows
```

Or run a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server
```

Then visit `http://localhost:8000`

### Configuration

Add your weather API key in the JavaScript file:
```javascript
const API_KEY = 'your_api_key_here';
```

## 📖 How to Use

1. **Allow Location** – Grant permission for location access
2. **View Current Weather** – See conditions for your location
3. **Search City** – Enter city name to look up weather
4. **Check Forecast** – View upcoming weather trends
5. **Toggle Units** – Switch between °C and °F

## 🌡️ Information Displayed

- Current temperature and "feels like" temperature
- Weather condition (Clear, Cloudy, Rainy, etc.)
- Humidity percentage
- Wind speed and direction
- UV index
- Visibility
- Air pressure
- Sunrise/sunset times

## 📱 Responsive Layout

- **Desktop** – Full dashboard layout
- **Tablet** – Optimized card view
- **Mobile** – Single column layout

## 📝 License

This project is open source and available under the MIT License.

---

Built with ❤️ by [Scarface96](https://github.com/Scarface96)