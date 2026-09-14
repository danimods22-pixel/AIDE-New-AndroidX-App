# AIDE-New-AndroidX-App

**AIDE New AndroidX App** - A weather dashboard application for Android built with modern AndroidX libraries.

## Features

- 🌤️ Real-time weather data from OpenWeatherMap API
- 📍 Location-based weather information
- 🔄 Auto-refresh weather data
- 🎨 Modern Material Design UI
- 📱 Responsive layout for all screen sizes
- 🌙 Support for multiple weather conditions
- ⚡ Efficient API calls with caching

## Tech Stack

- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **API**: OpenWeatherMap
- **Libraries**:
  - AndroidX (AppCompat, ConstraintLayout)
  - Retrofit2 (HTTP Client)
  - Gson (JSON Parser)
  - LiveData & ViewModel
  - Coroutines
  - Glide (Image Loading)

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/weatherdashboard/
│   │   │   ├── api/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── viewmodel/
│   │   │   ├── ui/
│   │   │   └── MainActivity.kt
│   │   ├── res/
│   │   └── AndroidManifest.xml
│   └── test/
└── build.gradle
```

## Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- Android SDK 21 (Minimum)
- OpenWeatherMap API Key (Get it free at [openweathermap.org](https://openweathermap.org/api))

### Installation

1. Clone the repository
2. Add your OpenWeatherMap API key in `local.properties`:
   ```
   WEATHER_API_KEY=your_api_key_here
   ```
3. Build and run the app

## API Reference

Using OpenWeatherMap Current Weather Data API:
- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Parameters**: 
  - `q` - City name
  - `appid` - API Key
  - `units` - Temperature units (metric/imperial)

## Screenshots

Coming soon...

## License

This project is open source and available under the MIT License.

## Author

- **danimods22-pixel** - Initial work
