# Weather-App
## 🌤 Smart City Weather Dashboard

### 🌅 Description
Smart City Weather Dashboard is a web application that provides detailed real-time weather information for any city using the OpenWeather API.

Beyond just temperature, the app also gives "What to Wear" advice based on weather conditions (for example: "Bring an umbrella!" if rain > 20%).  
The dashboard can automatically detect the user's location using the browser Geolocation API and load the local weather.

The app also shows environmental details like Air Quality Index, humidity, wind speed, pressure, sunrise/sunset time, and more to help users plan their day.

---

### 🎆 Features

- Search weather by city name  
- Auto-detect location using browser Geolocation API  
- Current temperature with dynamic background colors  
- What to Wear suggestions based on weather conditions  
- 5-day weather forecast  
- Hourly weather forecast  
- Dynamic weather icons based on weather codes  
- Air Quality Index (AQI)  
- Humidity  
- Wind speed  
- Feels like temperature  
- Visibility  
- Sunrise & Sunset time  
- Atmospheric pressure
- Responsive design (works on laptop, mobile, and tablet)
-  Dark / Light mode
- Save favorite cities and sort them alphabetically
- Background color changes based on temperature  
  - Blue → Cold  
  - Black/White → Normal  
  - Orange → Hot  

---

### 🛠 Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API
- Geolocation API (maybe)

Public API used:  
https://openweathermap.org/api

---

### ⚙️ How It Works

1. User enters a city name or allows location access
2. App fetches weather data from OpenWeather API
3. UI updates dynamically with:
   - Weather data
   - Icons
   - Background color
   - Clothing advice
4. Additional API calls fetch forecast and AQI data

---

### 🎨 UI Ideas

- Dynamic background color based on temperature
- Weather icons change based on weather condition
- Clean dashboard layout
- Responsive design

---

### 🎯 Challenges Implemented

- Using Geolocation API
- Handling multiple API endpoints
- Converting UNIX time to sunrise/sunset
- Mapping weather codes to icons
- Showing AQI data
- Dynamic UI updates
- Hourly + daily forecast rendering

---

### 🔮 Future Improvements

- Weather alerts

---

### 📜 License

This project is for learning purposes.
