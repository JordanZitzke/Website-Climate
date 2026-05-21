# 🌤️ What's Weather

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://marcelodanigno.github.io/ProjetoClimaDistribuido/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**What's Weather** is a modern web application for real-time weather forecasting and geolocation tracking. Developed as my undergraduate graduation project, it provides users with accurate, location-based climate data through an intuitive and responsive interface.

## 🚀 Live Preview

Experience the application in your browser: **[What's Weather - Live Site](https://marcelodanigno.github.io/ProjetoClimaDistribuido/)**

## ✨ Features

* **Real-time Weather Data:** Get accurate and up-to-date weather forecasts based on precise coordinates.
* **Geolocation Support:** Automatically search and retrieve weather data based on the user's current or requested location.
* **Responsive Design:** A clean, user-friendly interface optimized for both desktop and mobile devices.
* **Modern Tooling:** Fast and optimized development environment built with Vite.

## 🛠️ Tech Stack

* **Frontend:** JavaScript (Vanilla), HTML5, CSS3
* **Bundler/Dev Server:** [Vite](https://vitejs.dev/)
* **External APIs:** 
  * [Open-Meteo Weather API](https://open-meteo.com/en/docs)
  * [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)

## ⚙️ Getting Started

To run this project locally on your machine, follow these steps:

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) and `npm` installed.

### Installation

1. Clone this repository:
```bash
git clone [https://github.com/JordanZitzke/Website-Climate.git](https://github.com/JordanZitzke/Website-Climate.git)
```

2. Navigate to the project directory:
```bash
cd Website-Climate
```

3. Install the required dependencies:
```bash
npm install
```

### Running the Development Server

Start the local Vite server by running:
```bash
npm run dev
```

The terminal will provide a local address (usually `http://localhost:5173`) where you can view and interact with the application.

## 📚 API Reference

This project relies on the **Open-Meteo API** for its core data. Open-Meteo is a fast, open-source weather API that does not require API keys, making it highly accessible for this architecture.

* **Weather API Parameters:** For a complete list of available metrics, refer to the [Open-Meteo Weather API Documentation](https://open-meteo.com/en/docs).
* **Geocoding API Parameters:** For location search details, consult the [Open-Meteo Geocoding API Documentation](https://open-meteo.com/en/docs/geocoding-api).

## 📄 License

This project is licensed under the [MIT License](LICENSE).
```
