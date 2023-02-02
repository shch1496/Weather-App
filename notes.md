## Weather App
API used -> https://openweathermap.org/api
1. Current Weather Data
2. 5 Day / 3 Hour Forecast

* We need API key to communicate with the service.
* Use json hero -> To show the json info

* To format the time:
  Intl.DateTimeFormat("en", {
    hour12: true,
    hour: "numeric",
  });
