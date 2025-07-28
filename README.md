# 🌤️ Simple Weather App (Python - OpenWeatherMap)

This is a simple Python script that fetches and displays current weather information for a city entered by the user. It uses the **OpenWeatherMap API** to retrieve real-time weather data such as temperature and description.

---

## 📌 Features

- Takes **API key** and **city name** as user input
- Uses the **OpenWeatherMap API** to fetch weather data
- Displays:
  - City name and country
  - Temperature in Celsius
  - Weather condition description (e.g. "clear sky", "light rain")
- Simple error handling (invalid API key, invalid city, or failed request)
- Prints raw API response if something goes wrong (for debugging)

---

## 📦 Skills Practiced

This small project helps practice the following key Python and web-related skills:

- ✅ Working with **APIs** (sending GET requests, parsing JSON)
- ✅ Using **Python input/output**
- ✅ Handling **HTTP responses** and basic error checking
- ✅ Using the `requests` library
- ✅ String formatting (f-strings)
- ✅ Cleaning user input with `.strip()`
- ✅ Reading and understanding API documentation

---

## ⚙️ Requirements

- Python 3.x  
- Internet connection  
- An [OpenWeatherMap API key](https://openweathermap.org/api) (free signup)

---

## ▶️ How to Run

You can run this code in any Python environment (like VSCode, PyCharm, or terminal), or directly in **Google Colab**.

### 🔹 Option 1: Google Colab

1. Go to [https://colab.research.google.com](https://colab.research.google.com)
2. Create a **new notebook**
3. Paste the code into a code cell
4. Run the cell
5. Enter your **API key** and **city name** when prompted

### 🔹 Option 2: Local Machine

1. Make sure `requests` is installed:
   ```bash
   pip install requests
