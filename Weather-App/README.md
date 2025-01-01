# Weather Web Application

A dynamic weather web application that fetches real-time weather data using a weather API. Users can view current weather conditions, temperature, and other relevant information based on their location or a manually entered location.

## Features

- **Geolocation Support:**
  - Automatically fetches the user's location (with permission) to display local weather.
- **Manual Location Input:**
  - Allows users to input a location manually to view its weather data.
- **Current Weather Details:**
  - Displays temperature, weather conditions, humidity, wind speed, and more.
- **Interactive UI:**
  - Clean and responsive design for seamless user experience.

## Technologies Used

- **HTML:** Structured the layout of the application.
- **CSS:** Styled the interface to ensure responsiveness and visual appeal.
- **JavaScript:**
  - Fetches data from the weather API.
  - Handles geolocation and manual location input.
  - Updates the DOM dynamically to display weather details.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-web-app.git
   ```

2. Open the project folder:
   ```bash
   cd weather-web-app
   ```

3. Obtain an API key from a weather service provider (e.g., OpenWeatherMap).

4. Add your API key to the `script.js` file:
   ```javascript
   const API_KEY = 'your_api_key_here';
   ```

5. Open the `index.html` file in your browser to use the application.

## File Structure

```
weather-web-app/
├── main.html      # Main HTML file
├── styles.css      # CSS file for styling the application
├── script.js       # JavaScript file for functionality
└── README.md       # Project documentation
```

## Customization

- Modify `styles.css` to adjust the color scheme, fonts, or layout.
- Enhance `script.js` to display additional weather information like a weekly forecast or weather icons.

## Contributing

Contributions are welcome! If you have ideas for improvements or additional features, feel free to open an issue or submit a pull request.
