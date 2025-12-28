# Weather App with React, TanStack Query, Shadcn UI, Recharts, Tailwind, and TypeScript

## Overview

A modern weather dashboard built with React and TanStack Query, providing real-time weather information and forecasts with a clean, responsive interface.

## Features

- Current weather details
- 5-day weather forecast
- Location search functionality
- Reverse geocoding for current location
- Metric units for temperature and wind speed
- Responsive design for all devices
- Dark and light mode support

## Tech Stack

- Frontend: React 18, Vite
- Data Fetching: TanStack Query (React Query)
- Styling: Tailwind CSS, Shadcn UI
- Visualization: Recharts
- Language: TypeScript
- API: OpenWeatherMap API

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- OpenWeatherMap API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/duy-debug/weather-app.git
cd weather-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a .env file in the root directory and add your OpenWeatherMap API key:
```
VITE_WEATHER_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

## API Integration

The application integrates with the following OpenWeatherMap API endpoints:
- Current Weather Data
- 5-Day / 3-Hour Forecast
- Geocoding API (Location Search)
- Reverse Geocoding API

## Project Structure

```
src/
├── api/          # API integration and type definitions
├── components/   # Reusable UI components
├── hooks/        # Custom React hooks
├── pages/        # Main application views
├── lib/          # Shared utilities and configurations
└── context/      # Context providers
```

## Credits

- Weather data provided by OpenWeatherMap
- Data fetching solution by TanStack Query
- UI components by Shadcn UI and Radix UI
- Charts by Recharts

## License

This project is licensed under the MIT License.
