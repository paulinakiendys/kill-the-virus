# socket.io-game

Simple [2 player game](http://kill-the-virus-powerpuff.herokuapp.com/) built using [Node.js](https://nodejs.org/en/), [Express](https://expressjs.com/), [Socket.io](https://socket.io/) and [MongoDB](https://www.mongodb.com/).

## Table of contents
* [Requirements](#requirements)
* [Knowledge](#knowledge)
* [Screenshots](#screenshots)
* [Specification](#specification)
* [Timeline](#timeline)

## Requirements

- version control using Git
- deployed to Heroku

## Knowledge

### A few skills I've improved during this project:

- collaboration using GitHub
- effective communication using Microsoft Teams
- project management using Trello

## Screenshots

### Start view

![Start](./screenshots/Screenshot%202022-03-28%20at%2010-46-02%20Kill%20the%20virus.png)

### Lobby view

![Lobby](./screenshots/Screenshot%202022-03-28%20at%2010-47-53%20Kill%20the%20virus.png)

### Game view

![Game](./screenshots/Screenshot%202022-03-28%20at%2011-53-43%20Kill%20the%20virus.png)

### Winner view

![Winner](./screenshots/Screenshot%202022-03-28%20at%2011-54-22%20Kill%20the%20virus.png)


## Specification

- player must be able to enter a username
- points must be calculated on the server-side
- show timer and latest reaction time for both players
- multiple games should be able to run at the same time
- display a message saying: "Waiting for another player..." when a player connects
- start game as soon as two players are connected
- create a game lobby to show:
    - ongoing games and their score updated in realtime.
    - highscore (fastest average reaction time). Highscore should be stored in a database.
    - 10 most recent games. Game history should be stored in a database.

## Timeline

approx. 2 weeks