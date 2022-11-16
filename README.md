# Bingo!
This is an online dingo game. Here is the data diagram:

## APIs
[Join Game](README.md#join-game)

[Pay Anti Up](README.md#anti-up)

[Draw Cards](README.md#draw-cards)

## Join Game
This API allows the user to join the game. It uses the "GET" HTTP method.

Sample Call:
```http
http://bingo.come/api/joingame?name=Heather
```
This allows a player named Heather to join the game.
Sample Responce:
```javascript
{"status": "success"}
```
Sample Error:
```javascript
{"status": "fail-player not old enough"}
```

## Anti Up

## Draw Cards
