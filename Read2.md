# City Explorer APIs

## Weather API Documentation

With the Weather API that I used, you can get real-time weather data from live weather stations, as well as historical weather data stations, doppler radar, satellite, and atmospheric re-analysis products over the previous 10 years. Also, highly localized weather forecasts for every location on the planet, based on the world's most reliable weather models!

You may seek for weather information using a variety of techniques, including:

- Latitude/longitude
- City name
- City ID
- Weather station ID
- Airport ICAO code
- Postal code

## Weather API usage

I used the Weather Forecasts in this API server.\
To get the weather for todays and the 5 days ahead with description and date.\
And it gives back the Ctiy name and Latitude longitude, for that city.

## Weather API Endpoints/Request URLs

I used Heroku to publish my API to the public with this [Link](https://ismaelscity.herokuapp.com/), this link get you to the main route, and this [Link](https://ismaelscity.herokuapp.com/getWeather?city=Amman) get you to the weather API for Amman you can change it by changing the name of the city you want in the URL, so if you want Paris you just put Paris infront of city=, like this (https://ismaelscity.herokuapp.com/getWeather?city=Paris).

## Weather Authentication Key

Client users and apps using REST APIs provide API keys in order to track and manage how the APIs are used (for example, to meter access and prevent abuse or malicious attack). The Authenticate API Key filter lets you use the API Gateway to safely authenticate an API key.

So each client that what to use an API like the weather API he need to get an authentication key so the server just send this data to him and him only.

## Movie API Documentation

The API service is for anybody who wants to use their movie, TV show, or actor pictures and/or data in their program. Their API is a mechanism that allows you and your team to retrieve and use their data and/or photos in a programmed manner.

-------

## Movie API usage

I used themoviedb in my application.\
So I can get some info about the movie I want like

- Title
- Overview
- Avrage vote
- Total votes
- Poster of the movie
- Popularity
- And when it was released.

## Movie API Endpoints/Request URLs

I used Heroku to publish my API to the public with this [Link](https://ismaelscity.herokuapp.com/), this link get you to the main route, and this [Link](https://ismaelscity.herokuapp.com/getMovie?city=Paris) get you to the Movie API for Paris so any movie that have the word Paris in it the info of this movie will be shown on the screen, you can change it by changing the name of the Movie you want in the URL, so if you want Jordan you just put Jordan infront of city=, like this (https://ismaelscity.herokuapp.com/getMovie?city=Jordan).

## Movie Authentication Key

On version 3, application-level authentication is managed by api key, a single query parameter, or by using your v4 access token as a Bearer token. Log in to your TMDB account and select the "API" link on the left hand sidebar of your account page to get an API key.

[Weather API](https://www.weatherbit.io/api)

[Weather key](https://docs.oracle.com/cd/E65459_01/dev.1112/e65461/content/authn_api_key.html)

[Movie API](https://www.themoviedb.org/documentation/api)

[Movie key](https://developers.themoviedb.org/3/getting-started/authentication)