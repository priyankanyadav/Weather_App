# Weather_App
The Open Weather App is a simple web app that fetches current weather for a city using the OpenWeather API. Users enter a city name and the app displays Temperature, Feels like, Min temp, and Max temp in °C. It demonstrates DOM manipulation, the Fetch API with async/await, basic error handling, and working with third-party APIs.
# Open Weather App

A lightweight web app that fetches current weather data for a given city using the [OpenWeather](https://openweathermap.org/) API.  
It displays:

- 🌡️ **Temperature** (`main.temp`)
- 💦 **Feels like** (`main.feels_like`)
- 📉 **Min temp** (`main.temp_min`)
- 📈 **Max temp** (`main.temp_max`)

If an invalid city is entered, all values are set to **0** and the browser console shows a **404** error — per assignment requirements.

---

## ✨ Features
- Simple UI with a single input for **City**
- Uses **Fetch API** with **async/await**
- Graceful error fallback (sets values to `0` on 404)
- Minimal styling via **Sakura.css** CDN
- Easy to run locally with **Live Server**

---

## 📦 Tech Stack
- **HTML5** (semantic structure)
- **JavaScript (ES6+)**: Fetch API, async/await
- **CSS**: Sakura.css (CDN)
- **OpenWeather API**

---

## 🗂️ Project Structure
