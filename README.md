# 🌍 Aero Weather (3D Premium)

A sleek, premium weather application featuring an interactive 3D Globe, real-time weather data, and a modern glassmorphism UI. Search for any city or drop a pin anywhere on Earth to get instant weather updates and explore the location.

![Aero Weather Screenshot](https://raw.githubusercontent.com/debojitbhowmick2006-create/Weather-with-maps/main/screenshot.png) *(You can add a screenshot here later)*

## ✨ Features

- **Interactive 3D Earth:** Powered by `Globe.gl` and `Three.js`, the background features a stunning, draggable 3D globe with atmospheric glow and realistic textures.
- **Real-Time Global Weather:** Fetches live temperature, humidity, wind speed, and weather conditions using the free [Open-Meteo API](https://open-meteo.com/).
- **Premium Glassmorphism UI:** Features a sleek dark mode, frosted glass panels (`backdrop-filter`), smooth CSS animations, and a modern typography stack (*Plus Jakarta Sans*).
- **Embedded 2D Mini-Map:** Automatically opens a sleek, dark-themed 2D street map (`Leaflet.js`) inside the weather card so you can see the local geography.
- **Deep-Zoom Animations:** Searching for a city or clicking on the globe triggers a smooth, cinematic camera fly-in to the specific location.
- **Google Maps Integration:** Instantly open any searched or clicked coordinate directly in Google Maps with one click.
- **Geolocation Support:** Instantly find the weather for your current physical location.

## 🚀 Built With

- **Vanilla HTML / CSS / JavaScript** (No build tools required!)
- **[Globe.gl](https://globe.gl/)** & **Three.js** (3D Earth rendering)
- **[Leaflet.js](https://leafletjs.com/)** (2D Mini-Map)
- **[Open-Meteo API](https://open-meteo.com/)** (Weather forecasting & Geocoding)
- **[Nominatim (OpenStreetMap)](https://nominatim.org/)** (Reverse geocoding)
- **CartoDB** (Dark map tiles)

## 🛠️ Quick Start (How to Run)

Since this project uses pure HTML, CSS, and JavaScript with public APIs, there is no complicated build process or API keys required. You can clone and run it in a single command!

Open your terminal and run:

```bash
git clone https://github.com/debojitbhowmick2006-create/Weather-with-maps.git && cd Weather-with-maps && python -m http.server 8080
```

*Don't have Python? You can also use `npx http-server -p 8080`, or simply open the `index.html` file directly in your web browser!*

Once the server is running, visit **http://localhost:8080** in your web browser to view the 3D globe!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check [issues page](https://github.com/debojitbhowmick2006-create/Weather-with-maps/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
*Designed for a premium interactive weather experience.*
