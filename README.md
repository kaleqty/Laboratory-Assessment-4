
![index html - WEATHER-APP - Visual Studio Code 17_03_2025 4_53_13 pm](https://github.com/user-attachments/assets/90a07f9a-7518-4737-97e2-a33fb433fdb3)


# React Weather App  

The **React Weather App** is a simple yet interactive weather application that allows users to check the current weather conditions for any city worldwide. It fetches real-time weather data from the **OpenWeatherMap API** and displays details like temperature, humidity, wind speed, and weather icons dynamically.

---

## Features  

✅ **Live Weather Data** – Fetches real-time weather data based on user input.  
✅ **City Search Functionality** – Users can search for weather updates in any city.  
✅ **Dynamic UI Updates** – Uses React state management to update weather information without refreshing the page.  
✅ **Responsive Design** – Optimized for mobile and desktop devices.  
✅ **Custom Weather Icons** – Displays weather icons based on OpenWeatherMap conditions.  
✅ **Background Image & Theme** – Includes a gradient background and transparent overlay for better visibility.  

---

## API Source  

This app uses the **OpenWeatherMap API** to fetch weather data.  
[OpenWeatherMap API](https://api.openweathermap.org/data/2.5/weather?q={city}&units=metric&appid={API_KEY})

---

## Installation & Usage  

1 **Navigate to the project folder:**  
```bash
cd react-weather-app
```
2 **Install dependencies:**
```bash
npm install
```
3 **Create a .env file in the root directory and add your OpenWeatherMap API Key:**
```bash
VITE_APP_ID="your_api_key_here"
```
4 **Start the development server:**
```bash
npm run dev
```
5 **Open your browser and visit:**
```bash
[npm run dev](http://localhost:5173/)
```

---

## useState
**useState is used to manage the weather data state. It helps store values like temperature, wind speed, and humidity.**
```js
const [weatherData, setWeatherData] = useState(false);
```

##useEffect
**useEffect is a built-in React hook that performs side effects in function components. In this Weather App, useEffect is used to fetch default weather data when the component first mounts.**
```js
useEffect(() => {
    search("New York");
}, []);
```
