# 🌤️ Weather App

A simple and elegant weather application built using **HTML**, **CSS**, and **JavaScript** that fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api).

---

## 🚀 Features

- 🌍 Search for weather information by **city name**
- 🌡️ Displays **current temperature**, **min/max temperature**
- 🌦️ Shows **weather type** (e.g., Clear, Rain, Snow, etc.)
- 📅 Displays the current **date and location**
- 🎨 Dynamic background images based on weather type
- 🔍 Clean and responsive user interface


## 📸 Screenshots
> ---<img width="1279" alt="Screen Shot 2025-04-20 at 2 18 59 PM" src="https://github.com/user-attachments/assets/5844e0f2-1119-4378-960c-6c0cede1c298" />

---

## 🧠 Technologies Used

- **HTML5** – Markup structure  
- **CSS3** – Styling and layout  
- **JavaScript (ES6)** – Logic and API interaction  
- **OpenWeatherMap API** – Real-time weather data

---

## 🛠️ How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Open the App

You can run it in 3 ways:

#### 📁 Method 1: Open in Browser

```bash
# Windows
start weather_index.html

# macOS
open weather_index.html

# Linux
xdg-open weather_index.html
```

#### 🔥 Method 2: Use Python HTTP Server

```bash
# Python 3.x
python -m http.server 8000

# Then open in browser:
http://localhost:8000/weather_index.html
```

#### 🌐 Method 3: VS Code Live Server

1. Open the project folder in **VS Code**  
2. Install the **Live Server** extension  
3. Right-click `weather_index.html` → **Open with Live Server**

---

## 🔑 API Key Setup

This app uses a hardcoded API key in `app.js`:

```js
const weatherApi = {
    key: "YOUR_API_KEY",
    baseUrl: "https://api.openweathermap.org/data/2.5/weather"
};
```

You can get your own key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) for free.

---

## 📁 Project Structure

```
weather-app/
│
├── app.js                # Main JavaScript file
├── weather_index.html    # HTML file (entry point)
├── weather_style.css     # Stylesheet
├── images/               # Weather background images
├── README.md             # This file
└── ...
```

---

## 🙌 Author

**Akshit Singh**  
📫 [LinkedIn](www.linkedin.com/in/akshit-singh-aba4b51a6) • ✉️ akshit.singh0319@gmail.com

---

## ⭐️ Show Your Support

If you like this project, give it a ⭐️ on [GitHub](https://github.com/Akshit358/Weather-app-)!

---

## 📝 License

Feel free to improve it and build your own features on top!

```

