# WeatherNow 🌤️

A beautiful, responsive weather dashboard built with **vanilla HTML/CSS/JavaScript** ;no frameworks, no build tools.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![License](https://img.shields.io/badge/License-MIT-green)

---

## Features

- 🔍 **City search** — lookup any city worldwide
- 🌡️ **Celsius / Fahrenheit toggle** — persistent unit preference
- 📅 **5-day forecast** — with weather icons and high/low temps
- 💨 **Detailed stats** — humidity, wind speed, pressure, visibility, sunrise
- 🌿 **UV Index bar** — color gradient from low to extreme
- 🌬️ **Air Quality** — PM2.5 display with AQI badge
- 🎭 **Demo mode** — works without an API key using simulated data
- 📱 **Fully responsive** — mobile-first grid layout

---

## Quick Start

### Option 1 — Open directly in browser

```bash
git clone https://github.com/yourusername/weathernow.git
cd weathernow
open index.html  # or double-click the file
```

### Option 2 — With live API data

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Open `index.html` and replace line 148:
   ```js
   const API_KEY = 'YOUR_API_KEY'; // ← replace this
   ```
3. Refresh the browser

---

## Project Structure

```
weathernow/
├── index.html      # Complete app (HTML + CSS + JS in one file)
└── README.md
```

---

## API Endpoints Used

| Endpoint | Purpose |
|----------|---------|
| `/weather` | Current conditions for a city |
| `/forecast` | 5-day / 3-hour forecast data |

---

## Screenshots

The app includes:
- A dark glassmorphism-inspired current weather card
- Hover-animated 5-day forecast cards
- Gradient UV index progress bar
- Color-coded air quality badge

---

## Expanding the Project

Ideas for taking this further:

- **Geolocation** — auto-detect user location on load
- **Favorites** — save cities with localStorage
- **Charts** — hourly temperature curve using Chart.js
- **PWA** — add service worker for offline support
- **Dark/Light mode toggle**

---

## License

MIT — free to use, fork, and modify.
