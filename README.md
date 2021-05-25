# roBOT

![](https://img.shields.io/github/stars/danger-ahead/roBOT) ![](https://img.shields.io/github/forks/danger-ahead/roBOT) ![](https://img.shields.io/github/issues/danger-ahead/roBOT)

## Overview
- Uses [Numbers](https://rapidapi.com/divad12/api/numbers-1) from [RapidAPI](https://rapidapi.com/marketplace) for displaying year and math facts.
- Uses [Advanced Movie Search](https://rapidapi.com/jakash1997/api/advanced-movie-search ) from [RapidAPI](https://rapidapi.com/marketplace) for fetching movie details.
- Uses [DuckDuckGo](https://duckduckgo.com/) for fetching search results
- Uses [Free Dictionary API](https://dictionaryapi.dev/) for fetching meanings
- Uses [OpenWeatherMap API](https://openweathermap.org/api) for fetching weather details.

- Python Packages required:
	- [discord.py](https://pypi.org/project/discord.py/)
	- [duckduckgo-search](https://pypi.org/project/duckduckgo-search/)
	- [requests](https://pypi.org/project/requests/)
	- [python-decouple](https://pypi.org/project/python-decouple/)
	- [wikipedia](https://pypi.org/project/wikipedia/)

## Installation
- Head over to this [freecodecamp tutorial](https://www.freecodecamp.org/news/create-a-discord-bot-with-python/)
- Run `pip install -r requirements.txt`
- In the .env  file, paste the required keys as:
	` TOKEN=YOUR_TOKEN` (replace 'YOUR_TOKEN' with your token)
	`RAPID_API=YOUR_API_KEY` (replace 'YOUR_API_KEY' with your API key)
	`OPEN_WEATHER_TOKEN=YOUR_TOKEN` (replace 'YOUR_TOKEN' with your API key)

## Working
### roBOT reacts 👍 and 👎 after any successful and unsuccessful command execution respectively
#### For receiving year and math facts:
`_f y ` followed by the year
`_f m ` followed by the number
#### For performing a search
`_search ` followed by the search phrase
#### For finding the meaning of a word
`_mean ` followed by the word
#### For anonymous confessions (or perhaps anonymous chats ;) )
`_confess ` followed by the confession
#### For fetching movie details
`_movie ` followed by the name of the movie
#### For fetching weather details
`_wea ` followed by the name of the city(kolkata, melbourne etc), country code(au, us, in etc)
#### For performing search in Wikipedia
`_wiki ` followed by the search phrase
#### roBOT
`_hi`