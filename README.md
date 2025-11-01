🌦️ Weather App

A simple weather application built with HTML, CSS, and JavaScript that shows the current weather information for any city using the OpenWeather API.

🚀 Features

Search weather by city name

Shows temperature, humidity, and wind speed

Uses OpenWeather API for real-time data

Clean and responsive design

🧰 Setup Instructions
1️⃣ Clone or download this repository
git clone https://github.com/afzal786170/Weather-app.git

2️⃣ Open the project folder
cd Weather-app

3️⃣ Get your free API key from OpenWeather

Go to https://openweathermap.org/api

Click “Sign up” (if you don’t have an account)

After signing in, go to your API Keys page

Copy your default API key or create a new one

🔑 Add Your API Key

Open the script.js (or the JS file where API is called) and find this line:

const apiKey = "c1a577c2492d0b431beab7341e6657f9";


Replace the key inside quotes with your own API key, like this:

const apiKey = "YOUR_API_KEY_HERE";

▶️ Run the Project

Simply open the index.html file in your browser,
or use Live Server (VS Code extension) for a better experience.

🧠 Example
const apiKey = "YOUR_API_KEY_HERE";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";

🧾 Notes

Make sure your API key is active (it may take a few hours after creating).

Don’t share your API key publicly.

Free plan has request limits (60 calls/minute).
