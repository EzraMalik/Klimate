# 🌦️ Klimate - A Comprehensive Weather Forecast Application.

A modern, responsive **Weather Application** built with **React.js** and **TypeScript**, providing real-time weather data using the **OpenWeatherMap API**.
The app features a clean UI, efficient data fetching, and interactive weather visualizations.

---

## ✨ Features

- 🌍 Search weather by city
- 📍 Real-time weather data from OpenWeatherMap
- 📊 Interactive charts for temperature & weather trends
- ⚡ Fast and optimized data fetching with TanStack Query
- 🧠 Type-safe codebase with TypeScript
- 🌙 Dark mode toggle
- ⭐ Save favorite cities
- 📍 Geolocation-based weather
- 🗓️ 5-day forecast
- 🎨 Modern, accessible UI using shadcn/ui
- 📱 Fully responsive design

---

## 🛠️ Tech Stack

- **Framework:** React.js
- **Language:** TypeScript
- **UI Components:** shadcn/ui
- **Styling:** Tailwind CSS
- **State & Data Fetching:** TanStack Query (React Query)
- **Charts & Visualization:** Recharts
- **API:** OpenWeatherMap API

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/ezramalik/klimate.git
cd klimate
```

### 2️⃣ Install dependencies

```bash
npm install
# or
yarn install
```

### 3️⃣ Environment Variables

Create a .env.local file in the root directory and add:

```bash
VITE_OPENWEATHER_API_KEY=your_api_key_here
```

You can get an API key from:
👉 https://openweathermap.org/api

### ▶️ Running the App

```bash
npm run dev
# or
yarn dev
```
Open http://localhost:5173
 to view it in your browser.

 ---

 ## 📁 Project Structure

``` 
src/
├── api/                # API requests & data fetching logic
├── components/         # Reusable UI components
│   └── ui/             # shadcn/ui components
├── context/            # Global context providers (theme)
├── hooks/              # Custom hooks (weather, geolocation, favorites)
├── lib/                # Shared utilities & helpers
├── pages/              # Application pages & routes
├── App.tsx             # Root component
├── main.tsx            # Application entry point
└── index.css           # Global styles
```

### Architecture Overview

- Component-driven structure for maintainability and reuse
- TanStack Query manages API calls, caching, and async states
- Custom hooks encapsulate business logic and side effects
- Context API handles global UI state (theme)
- Recharts provides interactive weather visualizations
- LocalStorage persists user preferences and favorites

---

Built with ❤️ by Abdul using React.js, Typescript, Tailwind.css ,Tanstack Query, Shadcn/ui, Openweathermap API, Recharts.
