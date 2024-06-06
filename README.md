# weather-app
using node.js and ejs
Weather App
This is a simple weather application built with Node.js and Express that allows users to check the current weather for any location. The application fetches weather data from the OpenWeatherMap API and displays it on a dynamic EJS (Embedded JavaScript) template with CSS animations.

#Features
Real-time Weather Data: Fetches current weather data from the OpenWeatherMap API.
Location Search: Users can enter a location to get the current weather conditions.
Dynamic UI: Uses EJS to dynamically render weather information.
CSS Animations: Animated icons for clouds, rain, and humidity to enhance user experience.
#Technologies Used
Node.js: Server-side JavaScript runtime.
Express: Web application framework for Node.js.
EJS: Embedded JavaScript templating engine.
Axios: Promise-based HTTP client for making API requests.
CSS: Styling and animations for the user interface.
Setup and Installation
Clone the Repository

bash
Copy code
git clone https://github.com/saravananVIT/weather-app.git
cd weather-app
Install Dependencies

bash
Copy code
npm install
Create a .env File
Create a .env file in the root directory and add your OpenWeatherMap API key:

makefile
Copy code
API_KEY=your_openweathermap_api_key
Run the Application

bash
Copy code
npm start
The application will be running at http://localhost:3000.

Usage
Homepage: Enter the name of a city to get the current weather conditions.
Weather Information: Displays temperature, weather description, and humidity with animated icons.
