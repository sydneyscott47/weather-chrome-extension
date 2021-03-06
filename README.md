<!-- @format -->

# Weather Watcher: A Google Chrome Extension

**Climate Change is Real!**
:sunny: :umbrella: :cloud: :snowflake: :zap: :cyclone:


Weather Watcher was developed by Sydney Scott, Jackie Feit, and Betsy Groton for [Mintbean's Social Justice Hackathon](https://mintbean.io/). The purpose of the app is to show users the impact that global warming has had on their location, and make sustainability a priority in the user's life. The app can get the user's location using Geolocation API, or accept the user's input location and find the current weather in that place using Open Weather Map API.

<img src="https://media.giphy.com/media/ZbioT9xwNvb76HjmzA/giphy.gif" alt="location" />

The user can view how the temperature has changed in their location over the last 10 years in a chart designed with Victory.js. Lastly, the app uses Google's News API to show the top 3 headlines for that day related to the environment.

<img src="https://media.giphy.com/media/WD7GdVKKhRDdrfFjaR/giphy.gif" alt="weatherApp" />

You can view the full video walk-through [here](https://www.youtube.com/watch?v=36AS_etm0JM&feature=youtu.be)!


## Table of Contents

- [Overview](#Weather-Watcher:-A-Google-Chrome-Extension)
- [Table of Contents](#Table-of-Contents)
- [Download](#Download)
- [Team](#Team)
  - [Sydney Scott](#Sydney-Scott)
  - [Jackie Feit](#Jackie-Feit)
  - [Elizabeth Groton](#Elizabeth-Groton)
- [Tech Stack](#Tech-Stack)
- [Acknowledgements](#Acknowledgements)

## Download

**Step by step guide for downloading repo:**

```
cd <directory you want to download to>

git clone https://github.com/Jackie-Sydney-Betsy/weather-chrome-extension.git

npm install

npm run build

in your browser, go to [](chrome://extensions/), click "Load Unpacked," navigate to the repo on your machine, and choose the build folder

you'll need your own api keys (see details below) and to save them in a .env file in order to access weather and news data

click the extensions in the browser, and select the app's icon

enjoy :)

```

## Team

### `Sydney Scott`

LinkedIn: https://www.linkedin.com/in/sydneyroxanascott/

Github: https://github.com/sydneyscott47

### `Jackie Feit`

LinkedIn: https://www.linkedin.com/in/jackie-levine-feit/

Github: https://github.com/jackiefeit94

### `Elizabeth (Betsy) Groton`

LinkedIn: https://www.linkedin.com/in/elizabethgroton/

Github: https://github.com/betsyg6

## Tech Stack

- React

- Google Chrome Extension

- Various API's: [OpenWeatherMapAPI](https://openweathermap.org/current), [GeolocationAPI](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API), [WorldWeatherOnline](https://www.worldweatheronline.com/developer/api/docs/historical-weather-api.aspx), [GNewsAPI](https://gnews.io/)

## Acknowledgements

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
