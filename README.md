# 🌤️ Weather Forecast Web App

A responsive, modern **Weather Forecast Web App** built using **HTML, CSS, and vanilla JavaScript**, integrating real-time weather and air quality data from **OpenWeatherMap APIs**.  
This project demonstrates your ability to handle **REST APIs**, manipulate the **DOM**, and design clean, user-friendly UIs with **Bootstrap 5**.

---

## 🚀 Live Demo
🔗 [View Live Project](https://codingbee-gif.github.io/weather-forecast-app/)  
*(Replace with your GitHub Pages link once deployed)*

---

## 🧩 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **UI Framework:** Bootstrap 5
- **APIs Used:**
  - OpenWeatherMap **Current Weather API**
  - OpenWeatherMap **5-Day / 3-Hour Forecast API**
  - OpenWeatherMap **Air Pollution API**

---

## ✨ Features

- 🔍 **City Search:** Search weather details by city name.
- 🌡️ **Current Weather:** Displays temperature, feels-like, humidity, pressure, and weather description.
- 📅 **5-Day Forecast:** Shows upcoming daily weather trends.
- 🕓 **Today’s Hourly Forecast:** Displays temperature variation throughout the day.
- 💨 **Air Quality Metrics:** Displays **CO**, **NO₂**, **SO₂**, and **O₃** levels using the Air Pollution API.
- 🌅 **Sunrise & Sunset Times:** Converts UNIX timestamps into readable local times.
- 📱 **Responsive UI:** Designed with Bootstrap Grid and CSS Flexbox for all screen sizes.
- ⚡ **No Frameworks:** 100% vanilla JavaScript — no external JS libraries.

---

## 🧠 How It Works

1. User enters a **city name** in the input field.
2. JavaScript `fetch()` calls the **Current Weather API** to get weather data.
3. Extracts the coordinates (`lat`, `lon`) from the response.
4. Uses those coordinates to fetch:
   - The **5-day forecast** (`/data/2.5/forecast`)
   - The **air pollution data** (`/data/2.5/air_pollution`)
5. Updates the DOM dynamically using native JavaScript.
6. Displays data with weather icons, forecasts, and AQI readings.

---

## 🧰 Concepts Demonstrated

- REST API integration using `fetch()` and `async/await`
- JSON data parsing and UI rendering
- Dynamic DOM manipulation
- Date/time formatting using JavaScript `Date` methods
- Error handling for invalid or empty inputs
- Responsive design and layout with Bootstrap 5

---

## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/weather-forecast-app.git
