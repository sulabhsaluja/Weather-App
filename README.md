

# 🌦️ Weather App

A sleek and responsive weather forecast web app built using **HTML**, **CSS**, and **JavaScript**, powered by the [Tomorrow.io Weather API](https://www.tomorrow.io/). This app allows users to search for any city worldwide and get instant weather data along with a 5-day forecast.

## 🔗 Live Demo

[Click here to try it out](https://sulabhsaluja.github.io/Weather-App/)

## 🚀 Features

* 🔍 Search by city name
* 📍 Real-time weather data (temperature, wind speed, humidity, etc.)
* 🗓️ 5-day weather forecast
* 🌤️ Weather condition icons and summaries
* 📱 Fully responsive layout for mobile and desktop

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **API**: [Tomorrow.io Weather API](https://www.tomorrow.io/)
* **Icons**: Custom SVG weather icons (`/assets/weather/`)

## 🧩 Folder Structure

```
📁 Weather-App/
 ┣ 📂 assets/
 ┃ ┣ 📂 weather/       # Weather icons
 ┃ ┗ 📂 message/       # App screenshots
 ┃ ┗ bg.png
 ┣ 📜 index.html
 ┣ 📜 style.css
 ┣ 📜 script.js
 ┣ 📜 config.js        # (Ignored in git)
 ┣ 📜 .gitignore
 ┗ 📜 README.md
```

## 🔑 API Key Setup

This project uses the Tomorrow\.io API. To use your own key securely:

1. Get a free API key from [Tomorrow.io](https://app.tomorrow.io/signup)

2. Create a new file named `config.js` in the root of your project.

3. Add the following content:

   ```js
   // config.js
   const apiKey = "YOUR_API_KEY_HERE";
   ```

4. Add `config.js` to `.gitignore`:

   ```bash
   echo "config.js" >> .gitignore
   ```

5. Include `config.js` in your HTML **before** `script.js`:

   ```html
   <script src="config.js"></script>
   <script src="script.js"></script>
   ```

## 📦 Installation

To run the project locally:

```bash
git clone https://github.com/sulabhsaluja/Weather-App.git
cd Weather-App
open index.html
```

## 💡 Future Improvements

* 🌍 Add geolocation-based weather lookup
* 🌡️ Toggle between °C and °F
* 🌙 Add dark/light theme
* 🚨 Better error handling and offline support

## 📄 License

This project is open source and available under the [MIT License](LICENSE).


