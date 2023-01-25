# Weather App Coding Challenge

The goal is to build a React Native app that allows a user to search for a city, and display weather data for the cities that match the search.

The design and implementation is fully up to you, although we give more importance to functionality and code quality rather than to the look of the UI.

## Setup

Start with a blank React Native project (with TypeScript). Feel free to use the editor of your choice, or the online Expo editor https://snack.expo.io/.

You can use any third party library you want. You are allowed to use Google, StackOverflow, or whatever online resource get the answers you need.

Finally, you are encouraged to ask us questions, and to be as communicative as possible to explain your development process and decisions.

## Requirements

Display an input field where the user can type a city. Call the Geocoding API to obtain a list of cities matching the inputted query, and display the results in a list.

With the latitude/longitude returned by the Geocoding API, you can now call the Current weather data API to get the current weather for each result.

Create local types to enforce type safety on API results and in your local states.

Find a way to display the current weather data, either for all results, or for one result at a time (eg. as a result of some user interaction).

## Extra considerations

The API is rate limited, so you'll probably want to implement some strategy to avoid running over the usage limits.

## Using the OpenWeather API

You'll need to use two APIs. Please refer to the docs for more info:
- Geocoding API: https://openweathermap.org/api/geocoding-api
- Current weather data API: https://openweathermap.org/current

In both cases, you'll need an API Key. You can use this one:
```
d347e74a74bd1d098c187f6764fc0d28
```

Have fun!
