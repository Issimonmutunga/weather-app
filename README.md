# 🌦️ Weather Forecast App

A sleek, full-stack weather forecast app built with **Laravel API** (backend) and **Next.js (TypeScript + RippleUI)** frontend, powered by the OpenWeatherMap API. Users can search for any city and view real-time weather conditions, a 3-day forecast, and other useful details.

---

## 📦 Tech Stack

- **Frontend**: Next.js (TypeScript) + Tailwind CSS + RippleUI
- **Backend**: Laravel (API only, no Blade views)
- **API**: OpenWeatherMap (Current Weather + Geocoding + Forecast)
- **HTTP Client**: Laravel's built-in `Http::get()` via Guzzle

---

## 🔧 Features

- 🔍 City name search with Geocoding API
- 🌡️ Switch between °C and °F
- 🌤️ Display current weather icon, temperature, description
- 📍 Show date and location
- 📅 3-day weather forecast
- 💨 Wind status & 💧 Humidity info
- ⚡ Responsive design with RippleUI components

---

## 🚀 Getting Started

### 1. Backend (Laravel API)
```bash
# Create Laravel app
composer create-project laravel/laravel weather-api

# Move into the project folder
cd weather-api

# Run server
php artisan serve
