# Connect-Four-Final-Version

## [DEMO](https://bgoonzconnekt4.netlify.app/)

[![CodeFactor](https://www.codefactor.io/repository/github/bgoonz/connect-four-final-version/badge/master)](https://www.codefactor.io/repository/github/bgoonz/connect-four-final-version/overview/master)

![img](https://github.com/bgoonz/Connect-Four-Final-Version/blob/master/connekt4.PNG?raw=true)

[![Netlify Status](https://api.netlify.com/api/v1/badges/c0712cdc-ccb3-4edc-8516-17824b8d76dc/deploy-status)](https://app.netlify.com/sites/bgoonzconnekt4/deploys)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Connect Four</title>
    <link rel="stylesheet" href="./site.css" />
  </head>

  <body>
    <main>
      <div id="form-holder">
        <input id="player-1-name" placeholder="Player 1 Name" type="text" />
        <input id="player-2-name" placeholder="Player 2 Name" type="text" />
        <button id="new-game" disabled>New Game</button>
      </div>
      <div id="board-holder">
        <!-- class="is-invisible" -->
        <div id="click-targets">
          <div id="column-0" class="click-target"></div>
          <div id="column-1" class="click-target"></div>
          <div id="column-2" class="click-target"></div>
          <div id="column-3" class="click-target"></div>
          <div id="column-4" class="click-target"></div>
          <div id="column-5" class="click-target"></div>
          <div id="column-6" class="click-target"></div>
        </div>
        <div id="board-squares">
          <div id="square-0-0" class="token-square"></div>
          <div id="square-0-1" class="token-square"></div>
          <div id="square-0-2" class="token-square"></div>
          <div id="square-0-3" class="token-square"></div>
          <div id="square-0-4" class="token-square"></div>
          <div id="square-0-5" class="token-square"></div>
          <div id="square-0-6" class="token-square"></div>
          <div id="square-1-0" class="token-square"></div>
          <div id="square-1-1" class="token-square"></div>
          <div id="square-1-2" class="token-square"></div>
          <div id="square-1-3" class="token-square"></div>
          <div id="square-1-4" class="token-square"></div>
          <div id="square-1-5" class="token-square"></div>
          <div id="square-1-6" class="token-square"></div>
          <div id="square-2-0" class="token-square"></div>
          <div id="square-2-1" class="token-square"></div>
          <div id="square-2-2" class="token-square"></div>
          <div id="square-2-3" class="token-square"></div>
          <div id="square-2-4" class="token-square"></div>
          <div id="square-2-5" class="token-square"></div>
          <div id="square-2-6" class="token-square"></div>
          <div id="square-3-0" class="token-square"></div>
          <div id="square-3-1" class="token-square"></div>
          <div id="square-3-2" class="token-square"></div>
          <div id="square-3-3" class="token-square"></div>
          <div id="square-3-4" class="token-square"></div>
          <div id="square-3-5" class="token-square"></div>
          <div id="square-3-6" class="token-square"></div>
          <div id="square-4-0" class="token-square"></div>
          <div id="square-4-1" class="token-square"></div>
          <div id="square-4-2" class="token-square"></div>
          <div id="square-4-3" class="token-square"></div>
          <div id="square-4-4" class="token-square"></div>
          <div id="square-4-5" class="token-square"></div>
          <div id="square-4-6" class="token-square"></div>
          <div id="square-5-0" class="token-square"></div>
          <div id="square-5-1" class="token-square"></div>
          <div id="square-5-2" class="token-square"></div>
          <div id="square-5-3" class="token-square"></div>
          <div id="square-5-4" class="token-square"></div>
          <div id="square-5-5" class="token-square"></div>
          <div id="square-5-6" class="token-square"></div>
        </div>
        <div id="overlay"></div>
        <div id="game-name"></div>
      </div>
    </main>
    <script type="module" src="./connect-four.js"></script>
  </body>
</html>
```
