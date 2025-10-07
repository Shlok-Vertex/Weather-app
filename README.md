  # Weather App ☀️🌤️🌧️.   
  

A modern, intuitive, and feature-rich weather application that provides real-time weather information for any location worldwide. Get instant access to accurate weather data with a beautiful and responsive user interface.

![Weather App Screenshot](screenshots/weather-app.png)
*(Screenshot will be added once the app is styled)*

## ✨ Features. 

### Core Features
- 🔍 Search weather by city name or zip code
- 🌡️ Real-time weather data including:
  - Current temperature (°C/°F)
  - Feels like temperature
  - Humidity percentage
  - Wind speed and direction
  - Atmospheric pressure
  - Visibility
- 🎨 Dynamic weather icons based on conditions
- 📱 Fully responsive design for all devices
- 🌍 Support for multiple locations
- 📊 5-day weather forecast

### Additional Features
- 💾 Save favorite locations
- 🔄 Auto-refresh weather data
- 🌓 Dark/Light mode toggle
- 📍 Geolocation support
- 🔔 Weather alerts (when available)

## 🛠️ Technologies Used

- **Frontend:**
  - HTML5
  - CSS3 (with Flexbox/Grid)
  - JavaScript (ES6+)
  - Font Awesome Icons
  
- **APIs & Services:**
  - OpenWeather API
  - Geolocation API

## 🚀 Setup Instructions! 

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, or Edge)
- Text editor (VS Code recommended)
- API key from OpenWeather

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   ```

2. Navigate to project directory:
   ```bash
   cd weather-app
   ```

3. API Key Configuration:
   - Sign up at [OpenWeather](https://openweathermap.org/api)
   - Create a `.env` file in the root directory
   - Add your API key:
     ```env
     WEATHER_API_KEY=your_api_key_here
     ```

4. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

## 📁 Project Structure

```
Weather App/
├── assets/
│   ├── icons/         # Weather icons
│   └── images/        # App images
├── css/
│   ├── style.css      # Main styles
│   └── dark-mode.css  # Dark mode styles
├── js/
│   ├── script.js      # Main JavaScript
│   ├── api.js         # API handling
│   └── utils.js       # Utility functions
├── index.html         # Main HTML file
├── .env              # Environment variables
└── README.md         # Documentation
```

## 💻 Usage Examples

### Searching for a Location
1. Enter city name in the search bar
2. Press Enter or click the search icon
3. View detailed weather information

### Using Geolocation
1. Click the "Use My Location" button
2. Allow location access when prompted
3. View local weather data

### Saving Favorites
1. Search for a location
2. Click the heart icon
3. Access saved locations from the favorites menu

## 🔧 Troubleshooting

Common issues and solutions:

1. **API Key Issues:**
   - Verify `.env` file exists
   - Check API key is correctly formatted
   - Ensure API key is valid

2. **Location Not Found:**
   - Check spelling of city name
   - Try using zip code instead
   - Use country code (e.g., "London,UK")

3. **Geolocation Not Working:**
   - Enable location services in browser
   - Allow location access when prompted
   - Try refreshing the page

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact & Support

- Create an issue for bug reports or feature requests
- Send questions to: [mrmanishkr7911@gmail.com]

## 🙏 Acknowledgments

- OpenWeather API for weather data
- Font Awesome for icons
- Contributors and supporters

## 📅 Last Updated

2025-01-27

---
Made with ❤️ by [Shlok srivastava]
