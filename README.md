# Weather App README

## Introduction

Welcome to the Weather App! This application provides current weather information for any city using data from the OpenWeatherMap API. The app is built with HTML, CSS, and JavaScript, offering a clean and user-friendly interface to help you stay updated with the latest weather conditions.

## Features

- Search weather by city name
- Display current temperature, weather description, humidity, and wind speed
- Dynamic background based on weather conditions

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- A modern web browser (Chrome, Firefox, Safari, etc.)
- Internet connection to fetch data from OpenWeatherMap API

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/erinhdsilva/weather-app.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd weather-app
    ```

3. **Open `index.html` in your web browser:**
    You can double-click on the `index.html` file, or you can serve the files using a local server for better development experience.

### Configuration

1. **Get your API key from OpenWeatherMap:**
    - Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
    - Go to the API keys section and generate a new key.

2. **Set up your API key:**
    - Open `app.js` and find the following line:
        ```javascript
        const apiKey = 'YOUR_API_KEY_HERE';
        ```
    - Replace `'YOUR_API_KEY_HERE'` with your actual API key.

## Usage

1. **Search for a city:**
    - Enter the name of the city in the search input box.
    - Press the "Search" button or hit "Enter" to fetch the weather data.

2. **View weather details:**
    - The app will display the current temperature, weather description, humidity, and wind speed for the searched city.
    - Background image will change according to the weather condition.

## Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/api) for providing the weather data
- Inspiration from various weather apps and open-source projects

## Contact

For any questions or feedback, please contact erinhdsilva@gmail.com.

---

Enjoy using the Weather App and stay updated with the latest weather conditions!
