# Weather App

A simple and interactive weather application built using HTML, CSS, and JavaScript. The app fetches real-time weather data from the OpenWeatherMap API and displays the current weather conditions for any specified city.

## Features

- **Real-Time Weather Updates**: Get current temperature, weather description, and wind speed.
- **Weather Icon**: Displays an icon based on the current weather conditions.
- **User-Friendly Interface**: Minimalistic design with animated elements for a smooth experience.
- **Default Location**: Displays weather data for a default city (Patna) upon loading.

## Demo

![Weather App Screenshot (25)](https://github.com/user-attachments/assets/708a7bb6-6a86-45cd-9dba-567141394db6)


## Technologies Used

- **HTML**: For the structure of the app.
- **CSS**: For styling and layout.
- **JavaScript & jQuery**: For fetching and displaying weather data dynamically.
- **OpenWeatherMap API**: Provides real-time weather information.

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.)
- An internet connection to fetch weather data from the API.

### API Key

This application requires an API key from [OpenWeatherMap](https://openweathermap.org/). To use your own key:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/) to get a free API key.
2. Replace the `apiKey` variable in `script.js` with your own API key:

   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE';
   ```

### Installation

1. Clone the repository or download the files:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Open `index.html` in your web browser.

### Usage

1. Enter a city name in the input box.
2. Click on **Get Weather** to view the current weather for that city.

### Example Cities

Try these city names to see the app in action:

- New York
- London
- Paris
- Tokyo
- Mumbai

## Code Overview

- **index.html**: Contains the HTML structure and links to CSS and JS files.
- **style.css**: Holds the CSS styles for the application.
- **script.js**: Contains JavaScript functions for fetching weather data and updating the UI.
- **screenshot.png**: Optional screenshot of the app for documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for the weather API.
- [jQuery](https://jquery.com/) for simplifying JavaScript.

---

Feel free to contribute to this project by forking the repository and creating pull requests!

```

### Notes

1. Replace `YOUR_API_KEY_HERE` with your OpenWeatherMap API key in the code snippet.
2. If you want to include a screenshot, save it as `screenshot.png` in the same directory.
3. Update `your-username` in the GitHub link if you’re planning to host it on GitHub. 

This README provides a comprehensive overview for users and developers interested in the project.
