# WeatherApp 🌤️

A simple console-based weather application written in C# as a school project.

## About

WeatherApp fetches and displays current weather data for any city using the OpenWeatherMap API. It was built to practise C# fundamentals including HTTP requests, JSON parsing, and exception handling.

## Features

- Search current weather by city name
- Displays temperature, humidity, wind speed, and conditions
- Handles invalid city names and network errors gracefully

## Requirements

- .NET 6.0 or later
- An [OpenWeatherMap API key](https://openweathermap.org/api) (free tier)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/TomNelsonTembo/Weather-App-C-Project.git
   cd WeatherApp
   ```

2. Add your API key to `appsettings.json`:
   ```json
   {
     "ApiKey": "your_api_key_here"
   }
   ```

3. Run the app:
   ```bash
   dotnet run
   ```

## Usage

Enter a city name when prompted and the app will display the current weather conditions for that location.

```
Enter city name: Prague
----------------------------
City:        Prague, CZ
Temperature: 18°C
Feels like:  16°C
Humidity:    62%
Wind:        14 km/h
Conditions:  Partly cloudy
----------------------------
```

## Built With

- C# / .NET
- `HttpClient` for API requests
- `System.Text.Json` for parsing responses
- OpenWeatherMap API

## Author

Made as a school project. Feel free to use or adapt it for your own learning.
