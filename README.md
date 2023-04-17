# NBA-Game-Recap

Determines how exciting daily NBA games are using live data obtained from the NBA API, and concludes whether or not the game is worth watching. For games that are determined to be worth watching, searches for the highlight video from the NBA Youtube channel using the Youtube API.

## Preview:
<img src="https://i.imgur.com/hZdKpEu.png" width="450" height="300" />

## Features
- Uses the NBA API to obtain the daily game schedule as well as the game’s result and stats
- Evaluate the game and give a precap of whether the game is exciting enough to watch or not
- Allows user to pick specific teams/players that they want to track rather than every daily game
- Uses the Youtube API to recieve the highlight reel of each game from the NBA Youtube channel

## Files
- nba_api_helpers.py - Uses the NBA API and recieve game stats and results
- yt_api.py - Uses the Youtube API to recieve channel, playlist, and video 
- game_rater.py - Determines if the game is exciting or not

## Todo:
- Improve excitement determination
