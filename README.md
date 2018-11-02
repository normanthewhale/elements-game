### [Gameplay Instructions](https://docs.google.com/document/d/1HHIA1LgYNFDwX3jqK-7cGXw943NPmsdY-GeA4rEfUAA/edit?usp=sharing "Instructions")

### [Live Example](https://thawing-gorge-45352.herokuapp.com/ "Elements HerokuApp")


### Local Setup:
The App's back-end uses `Node.js` and runs on port 5000 while the front-end uses `React.js` and runs on port 3000. Game state is stored and updated on the back-end which then communicates with the `React` front-end via `Socket.io` to update state in the window.

#### Pre-Requisites:
 - Understanding of Elements' [rules](https://docs.google.com/document/d/1HHIA1LgYNFDwX3jqK-7cGXw943NPmsdY-GeA4rEfUAA/edit?usp=sharing "Instructions") of play.
 - Ability to clone GitHub repositories.
 - Must have `Node.js` installed.  

#### Setup:
 1. Clone the repo and `cd` into the `root` directory.
 2. Use `npm install` to install necessary server dependencies.
 3. When finished `cd client/` and again run `npm install` for front end dependencies.
 4. `cd` back into the `root` directory and use `npm run dev`. This will open a browser session of the app on `localhost:3000`.
 5. You will then need to open another browser to the same address.
 6. Once both browsers are open you may click `start game` at which point both windows will act as a seperate client and cards will be dealt to each.
 7. Commence playing. (Note that whichever browser instance clicked `start game` first will be the first player to take a turn.)
