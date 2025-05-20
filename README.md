<div align="center">
  <h1>🌤️ AtmosSphere</h1>
  <p>Interactive weather visualization built with Leaflet.js and OpenWeatherMap API</p>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/FalloutGhoulBusta/AtmosSphere/blob/main/CONTRIBUTING.md)
  [![GitHub stars](https://img.shields.io/github/stars/FalloutGhoulBusta/AtmosSphere?style=social)](https://github.com/FalloutGhoulBusta/AtmosSphere/stargazers)
  [![GitHub issues](https://img.shields.io/github/issues/FalloutGhoulBusta/AtmosSphere)](https://github.com/FalloutGhoulBusta/AtmosSphere/issues)
  [![GitHub forks](https://img.shields.io/github/forks/FalloutGhoulBusta/AtmosSphere?style=social)](https://github.com/FalloutGhoulBusta/AtmosSphere/network/members)
  [![GitHub watchers](https://img.shields.io/github/watchers/FalloutGhoulBusta/AtmosSphere?style=social)](https://github.com/FalloutGhoulBusta/AtmosSphere/watchers)
  [![Demo](https://img.shields.io/badge/Live-Demo-2ecc71?style=for-the-badge&logo=github)](https://falloutghoulbusta.github.io/AtmosSphere/)
  [![Contribute](https://img.shields.io/badge/Contribute-2980b9?style=for-the-badge)](CONTRIBUTING.md)
  [![Follow](https://img.shields.io/badge/Follow-1abc9c?style=for-the-badge&logo=github)](https://github.com/FalloutGhoulBusta)    
</div>

## 🌟 About

AtmosSphere is an interactive weather visualization application that brings weather data to life on an interactive map. Built with modern web technologies, it provides real-time weather information, air quality data, and beautiful visualizations to help you understand weather patterns at a glance.

🔍 **Explore** weather patterns in real-time  
🌡️ **Monitor** temperature, precipitation, and more  
🌬️ **Track** wind patterns and air quality  
📱 **Responsive** design that works on any device

## 🌟 Features

- **Interactive Map**
  - Real-time weather data visualization
  - Smooth panning and zooming
  - Responsive design for all devices

- **Weather Layers**
  - Temperature overlay with color gradients
  - Precipitation intensity visualization
  - Wind speed and direction
  - Humidity levels
  - Cloud cover
  - Atmospheric pressure

- **Air Quality Index (AQI)**
  - Real-time AQI data
  - Color-coded indicators
  - 5-category scale (Good to Hazardous)

- **User Experience**
  - Intuitive controls
  - Loading indicators
  - Error handling and user feedback
  - Mobile-friendly interface

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- An OpenWeatherMap API key (get one for free at [OpenWeatherMap](https://openweathermap.org/api))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/FalloutGhoulBusta/AtmosSphere.git
   cd AtmosSphere
   ```

2. Open `index.html` in your web browser

3. Enter your OpenWeatherMap API key in the settings menu (top-right corner)

## 🛠️ Usage

- Click anywhere on the map to view weather information for that location
- Toggle different weather layers using the layer control (bottom-right)
- View detailed weather information in the info panel (bottom-left)
- Use the hamburger menu (top-right) to update your API key if needed

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile Safari (iOS 10+)
- Chrome for Android

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Leaflet](https://leafletjs.com/) - For the amazing mapping library
- [OpenWeatherMap](https://openweathermap.org/) - For the weather data API
- [Font Awesome](https://fontawesome.com/) - For the icons

## 📬 Contact
For any questions or feedback, please contact me at [newmanngarry3@gmail.com](mailto:newmanngarry3@gmail.com).

Project Link: [https://github.com/FalloutGhoulBusta/AtmosSphere](https://github.com/FalloutGhoulBusta/AtmosSphere)

- Weather conditions with icons
  - Weather icon from OpenWeatherMap's icon service
  - Updates automatically when map is moved

- **Severe Weather Alerts**: 
  - Active weather alerts for the map center
  - Detailed alert information including event type and description
  - Source information for each alert

- **Dynamic Updates**: 
  - Automatic updates when panning or zooming
  - Real-time data refresh for all weather information
  - Loading indicators during data fetch

- **Geolocation**: 
  - Automatic centering on user's location
  - Fallback to default location if geolocation fails
  - Permission request for location access

## Technical Implementation

- **Map Library**: Leaflet.js v1.9.4
- **Weather Data**: OpenWeatherMap API
  - Current Weather API for basic weather data
  - Air Pollution API for AQI data
  - OneCall API (v3.0) for weather alerts
- **UI Styling**: 
  - Tailwind CSS for styling
  - Custom CSS for map controls and panels
  - Inter font family for text

## API Key Requirements

1. **Get an API Key**:
   - Sign up at [OpenWeatherMap](https://openweathermap.org)
   - Get a free API key
   - Note: Some features may require paid tier for full functionality

2. **API Key Features**:
   - Local storage persistence (API key is saved and automatically loaded)
   - Error handling for invalid keys
   - Loading state indicators
   - Automatic key validation
   - Persistent settings across sessions

## Setup and Usage

1. **Prerequisites**:
   - Modern web browser
   - Internet connection
   - OpenWeatherMap API key

2. **Running the Map**:
   - Open `index.html` in a web browser
   - Enter your API key in the input field
   - Click "Set Key & Load" to initialize

3. **Interacting with the Map**:
   - Use the layer control (top right) to toggle overlays
   - Pan and zoom to view different locations
   - View detailed weather information in the right panel
   - Click on AQI marker for more information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Error Handling

The application includes:
- Loading states for data fetch
- Error messages for API failures
- Fallbacks for geolocation failures
- Input validation for API key
- Graceful degradation for missing features

## Security

- API key is stored in browser local storage
- HTTPS required for API communications
- Input sanitization for API key
- Error handling for invalid API keys

## Known Limitations

- Some features may require paid OpenWeatherMap API tier
- Weather alerts may not be available in all regions
- AQI data availability may vary by location
- Map performance may vary with large data sets

## Contributing

If you'd like to contribute, please feel free to submit a pull request. We welcome improvements to:
- API error handling
- Map performance optimization
- UI enhancements
- Additional weather features
- Documentation improvements