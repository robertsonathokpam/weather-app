🌤️ Weather App
🧠 Overview

The Weather App is a simple and responsive web application that displays real-time weather data for any city in the world.
It uses the OpenWeatherMap API to fetch current weather conditions such as temperature, wind speed, humidity, and weather icons — all presented in a clean, modern UI.

🚀 Features

✅ Search weather by city name
✅ Displays temperature, wind speed, and humidity
✅ Shows weather-specific icons (sunny, clouds, rain, drizzle, mist, etc.)
✅ Handles invalid city names with an error message
✅ Responsive, mobile-friendly UI
✅ Footer with credits: “Created by Team Neon”

🛠️ Tech Stack
Technology	Purpose
HTML5	Page structure
CSS3	Styling and layout
JavaScript (ES6)	Dynamic data fetching and DOM manipulation
OpenWeatherMap API	Real-time weather data source
⚙️ How It Works

The user enters a city name in the search box.

On clicking the search button, the app sends a request to:

https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={your_api_key}


The API responds with live weather data, which the script displays dynamically on the page.

If the city name is invalid, an “Invalid City name” message appears.

🧩 File Structure
weather-app/
│
├── index.html        # Main HTML file
├── style.css         # Styles for layout and design
├── script.js         # JavaScript logic (API call and DOM updates)
├── img/              # Weather icons and search button image
│   ├── clouds.png
│   ├── clear.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── wind.png
│   ├── humidity.png
│   └── search.png
└── README.md         # Project documentation

🔑 API Setup

Go to OpenWeatherMap.org
.

Create a free account.

Generate your API key from the API Keys section.

Replace this line in your script.js with your own key:

const apiKey = "YOUR_API_KEY_HERE";

💻 How to Run Locally

Download or clone this repository:

git clone https://github.com/your-username/weather-app.git


Open the project folder:

cd weather-app


Open index.html in your browser — no server setup required!

🎨 UI Preview

💡 The design features a glassy gradient card with rounded corners, a search bar, and live weather info displayed below.

👨‍💻 Created By

Team Neon ⚡

Bringing creativity and simplicity together.
