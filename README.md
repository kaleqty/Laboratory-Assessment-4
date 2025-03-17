# React Weather App  

The **React Weather App** is a simple yet interactive weather application that allows users to check the current weather conditions for any city worldwide. It fetches real-time weather data from the **OpenWeatherMap API** and displays details like temperature, humidity, wind speed, and weather icons dynamically.

---

## Features  

**Live Weather Data** – Fetches real-time weather data based on user input.  
**City Search Functionality** – Users can search for weather updates in any city.  
**Dynamic UI Updates** – Uses React state management to update weather information without refreshing the page.  
**Responsive Design** – Optimized for mobile and desktop devices.  
**Custom Weather Icons** – Displays weather icons based on OpenWeatherMap conditions.  
**Background Image & Theme** – Includes a gradient background and transparent overlay for better visibility.  

---

## API Source  

This app uses the **OpenWeatherMap API** to fetch weather data.  
https://api.openweathermap.org/data/2.5/weather?q={city}&units=metric&appid={API_KEY}

## Installation & Usage  
**1 Navigate to the project folder**
cd react-weather-app
**2 Install dependencies:**
npm install
**Create a .env file in the root directory and add your OpenWeatherMap API Key:**
VITE_APP_ID="a3abf2a8f6cf45a5d8c1d3225b533cd5"
**Start the development server:**
npm run dev
