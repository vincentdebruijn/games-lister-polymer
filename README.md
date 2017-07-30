# gamelister
An app which shows the games/apps of a given developer on app stores (Steam, Google play) using Polymer.
Currently only loads dummy data.

## Installation
Run 
  npm install

## Run
Run
  npm start

## Test
Run
  npm test

If you get an error from Mocha that it expected a string, not undefined for title, fix the bug in web-components-tester's browser.js "new Mocha.Suite()". A string should be passed to the suite (the title of the test suite).
