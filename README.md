# Weather Application

**COMPANY:** CODTECH IT SOLUTIONS  
**NAME:** Tanush  
**INTERN ID:** CT04DG891  
**DOMAIN:** MERN Stack Web Development  
**DURATION:** 6 WEEKS  
**MENTOR:** NEELA SANTOSH  

---

## 🌤️ Project Overview

A beautiful, responsive weather application built with React and TypeScript that provides real-time weather information for any location worldwide. The app features an elegant design with dynamic backgrounds that change based on weather conditions and time of day.

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **5-Day Forecast**: View detailed weather predictions
- **Location Search**: Search for cities worldwide with autocomplete
- **Current Location**: Automatically detect and display weather for your current location
- **Dynamic Backgrounds**: Beautiful gradients that change based on weather conditions
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Weather Statistics**: Detailed metrics including humidity, wind speed, pressure, and more
- **Day/Night Themes**: Automatic theme switching based on sunrise/sunset times

## 🛠️ Technologies Used

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **API**: OpenWeatherMap API
- **Deployment**: Netlify

## 🚀 Live Demo

Visit the live application: [Weather App](https://celadon-pie-59ea97.netlify.app)

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd weather-application
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up API Key**
   - Sign up at [OpenWeatherMap](https://openweathermap.org/api)
   - Get your free API key
   - Update the API key in `src/utils/weatherApi.ts`

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 🏗️ Project Structure

```
src/
├── components/          # React components
│   ├── ErrorMessage.tsx    # Error handling component
│   ├── ForecastCard.tsx    # 5-day forecast display
│   ├── LoadingSpinner.tsx  # Loading animation
│   ├── SearchBar.tsx       # Location search functionality
│   ├── WeatherCard.tsx     # Main weather display
│   └── WeatherStats.tsx    # Additional weather metrics
├── types/              # TypeScript type definitions
│   └── weather.ts         # Weather data interfaces
├── utils/              # Utility functions
│   ├── weatherApi.ts      # API service layer
│   └── weatherUtils.ts    # Helper functions
├── App.tsx             # Main application component
├── main.tsx           # Application entry point
└── index.css          # Global styles
```

## 🎨 Design Features

- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Dynamic Backgrounds**: Weather-responsive gradient backgrounds
- **Glass Morphism**: Frosted glass effect with backdrop blur
- **Micro-interactions**: Hover effects and smooth transitions
- **Responsive Layout**: Mobile-first design approach
- **Accessibility**: Proper contrast ratios and semantic HTML

## 🌐 API Integration

The application integrates with OpenWeatherMap API to provide:
- Current weather conditions
- 5-day weather forecast
- Location geocoding
- Reverse geocoding for current location

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured layout with sidebar statistics
- **Tablet**: Adapted grid layout for medium screens
- **Mobile**: Stacked layout optimized for touch interaction

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌟 Key Components

### WeatherCard
Displays current weather conditions including temperature, description, and basic metrics.

### ForecastCard
Shows 5-day weather forecast with daily highs/lows and weather icons.

### SearchBar
Provides location search with autocomplete suggestions and current location detection.

### WeatherStats
Additional weather metrics including pressure, cloud coverage, and wind direction.

## 🎯 Learning Outcomes

This project demonstrates proficiency in:
- React functional components and hooks
- TypeScript for type safety
- API integration and error handling
- Responsive web design
- Modern CSS techniques (Tailwind CSS)
- State management in React
- Asynchronous JavaScript operations

## 🚀 Deployment

The application is deployed on Netlify with automatic builds from the main branch.

## 📄 License

This project is part of an internship program at CODTECH IT SOLUTIONS.

---

**Built with ❤️ by Tanush during MERN Stack Web Development Internship**