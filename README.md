# 🌤️ Weather App - React

A modern weather application built with **React**, **Bootstrap**, and **OpenWeatherMap API**. Get real-time weather information by entering latitude/longitude coordinates or using your current location.

![React](https://img.shields.io/badge/React-19.3.1-61DAFB?style=flat&logo=react)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat&logo=bootstrap)
![Axios](https://img.shields.io/badge/Axios-0.21.1-5A29E4?style=flat)
![License](https://img.shields.io/badge/License-MIT-green)

## 🎯 Features

- 🔍 **Search by Coordinates** - Enter latitude & longitude to get weather*
- 📍 **Geolocation Support** - Auto-detect user's current location
- 🌡️ **Real-time Weather** - Temperature, feels like, min/max temp
- 🌅 **Sunrise & Sunset** - Displays local times
- 🕒 **Recent Searches** - Saves history using LocalStorage
- ⚡ **Loading Spinner** - Smooth UX during API calls
- 📱 **Responsive Design** - Works on all screen sizes

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| React 19 | UI Framework |
| React Router v7 | Navigation |
| Axios | HTTP Requests |
| Bootstrap 5 | Styling |
| OpenWeatherMap API | Weather Data |
| Font Awesome | Icons |

## 🚀 Live Demo

- **Home:** `http://localhost:3000/`
- **Weather:** `http://localhost:3000/weather`




## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Zaid2694/Weather-App.git
cd Weather-App

2. Install dependencies
npm install

3. Start the development server
npm start
http://localhost:3000

🔑 API Configuration
This project uses OpenWeatherMap API. To use your own API key:

1.Get free API key from OpenWeatherMap

2.Open src/Components/Weather.js

3.Replace the API key in all axios calls:
appid=https://api.openweathermap.org/data/2.5/weather?lat=${this.state.lat}&lon=${this.state.lon}&appid=fc20873fd94177935c05130078ecabce&units=metric`


📁 Project Structure
my-react-project/
├── public/
├── src/
│   ├── Assets/
│   │   └── Loader.css
│   ├── Components/
│   │   ├── App.js
│   │   ├── Header.js
│   │   ├── Home.js
│   │   ├── Loader.js
│   │   ├── Recent.js
│   │   ├── Result.js
│   │   ├── Search.js
│   │   └── Weather.js
│   ├── index.js
│   └── reportWebVitals.js
└── package.json
  







