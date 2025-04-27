# 🌤️ Weather App

A simple and responsive Weather App built with **HTML**, **CSS**, and **JavaScript**, using the **OpenWeatherMap API** to fetch real-time weather data.

---

## 📸 Preview

<!-- Add a screenshot link if available -->
![Weather App Screenshot](#)

---

## 🚀 Features

- 🌍 Search and view weather for any city worldwide.
- 🌡️ Display temperature (°C), cloudiness (%), humidity (%), and pressure (hPa).
- 🏳️ Shows the country flag based on the location.
- 🌥️ Displays a weather condition icon dynamically.
- 🔍 Error animation if an invalid city name is entered.
- 🎨 Clean, modern, and responsive design.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **API:** [OpenWeatherMap API](https://openweathermap.org/api)
- **Icons:** [Font Awesome 6](https://fontawesome.com/)

---

## 📂 Project Structure

```
weather-app/
│
├── index.html       # Main HTML structure
├── styles.css       # Styling for the app
├── index.js         # JavaScript logic for fetching and updating data
└── README.md        # Project documentation
```

---

## 🔧 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prudhvisai26/Weather-App.git
   cd weather-app
   ```

2. **Open `index.html` in your browser.**

3. **Important:**  
   Replace the existing `appid` in `index.js` with your own OpenWeatherMap API key:
   ```javascript
   let id = "YOUR_API_KEY_HERE";
   ```

---

## 🌐 API Information

- This app uses the [Current Weather Data API](https://openweathermap.org/current) from OpenWeatherMap.
- Example API call:
  ```
  https://api.openweathermap.org/data/2.5/weather?q=London&units=metric&appid=YOUR_API_KEY
  ```

---

## 📋 Key Functionalities

- **Form Submission:**  
  Search by entering a city name and pressing the search button (magnifying glass icon).
  
- **Weather Data Updates:**  
  Upon successful search, updates:
  - City Name
  - Country Flag
  - Temperature
  - Weather Description
  - Cloudiness
  - Humidity
  - Pressure

- **Error Handling:**  
  If an invalid city is entered, the app triggers a short "shake" animation to indicate an error.

- **Default City:**  
  On initial load, the app displays weather for **San Jose** by default.

---

## 📈 Future Improvements (Ideas)

- Add **loading indicators** while fetching data.
- Include **5-day forecast** feature.
- Switch between **Celsius** and **Fahrenheit**.
- Add **geolocation support** to fetch weather for the user's current location automatically.
- Improve **error messages** with detailed feedback.

---

## 🙌 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for the amazing free API.
- [Font Awesome](https://fontawesome.com/) for beautiful icons.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

# 🌟 Show some love by giving a ⭐ if you like it!
