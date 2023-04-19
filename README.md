Weather App React
=================

This is a weather application built with React that allows users to search for the weather forecast of any city in the world. The app retrieves weather information from the OpenWeatherMap API.

Features
--------

-   Users can search for weather information by entering the name of a city
-   Weather information displayed includes temperature, weather description, wind speed, humidity, and pressure
-   App displays an appropriate background image based on the weather condition of the searched city
-   App displays an error message if the searched city is not found
-   App is responsive and can be viewed on different screen sizes

Getting Started
---------------

### Prerequisites

Before you can run the application, you need to have the following installed on your local machine:

-   Node.js (version 14 or higher)

### Installation

1.  Clone the repository

bashCopy code

`git clone https://github.com/tahiraydin/weather-app-react.git`

1.  Install dependencies

bashCopy code

`cd weather-app-react
npm install`

### Usage

1.  Get an API key from [OpenWeatherMap](https://openweathermap.org/api) by creating an account and subscribing to their API.
2.  In the `.env` file, replace `REACT_APP_API_KEY` with your API key.
3.  Start the application

sqlCopy code

`npm start`

1.  Open [http://localhost:3000](http://localhost:3000/) to view the app in the browser.

### Deployment

To deploy the app, you can use services like Netlify, Vercel, or Heroku.

Built With
----------

-   [React](https://reactjs.org/) - JavaScript library for building user interfaces.
-   [OpenWeatherMap API](https://openweathermap.org/api) - Weather API used to retrieve weather information.

Authors
-------

-   Your Name - Tahir Aydın(https://github.com/tahiraydin)

Acknowledgments
---------------

-   [Create React App](https://create-react-app.dev/) - React toolchain for creating applications.
-   [OpenWeatherMap](https://openweathermap.org/) - Weather API used in the app.
