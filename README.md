# Weather App
A simple weather app that allows users to search and save cities to view their weather information. The app fetches weather data from the [OpenWeather API](https://openweathermap.org/). The cities are saved to the browser's localStorage so that they persist even after a page reload.

## Features

- **Search for a city**: Enter a city name and get its current weather details.
- **Save cities**: Add cities to your list and retrieve weather data for them later.
- **Weather details**: Displays the current temperature, weather description, and wind speed.
- **Persistent data**: Saved cities are stored in localStorage, so they remain even after a page refresh.

## Demo

You can view the live demo of this weather app [here](https://amaanp32.github.io/WeatherSearch/).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
Navigate into the project directory:

bash
Copy code
cd weather-app
Open index.html in your browser to see the app in action.

Usage
Enter a city name in the input field and click the "Add City" button to fetch the weather data.
Once a city is added, click on any city from the list to see its weather details.
The list of cities will persist between sessions using the localStorage API.
Technologies Used
HTML for the structure of the app.
CSS for basic styling (optional, depending on your styling).
JavaScript for fetching weather data and interacting with localStorage.
API
This app uses the OpenWeather API. You can obtain your API key by signing up on their website. Replace the API key in the script with your own if needed.

Contributing
Fork the repository.
Create your feature branch (git checkout -b feature-name).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-name).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
