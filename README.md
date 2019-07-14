# dr-react-mario
*A multiplayer React implemntation of the classic "Tetris meets Dominoes" Dr. Mario*

## Background and Overview
Most MERN stack driven web app games are implemented by using JavaScript 
to manipulate the HTML `<canvas>` element. **dr-react-mario** eschews this traditional approach in favor of one that 
utilizes React's state managament and reusable components.

On arrival to the site, the user will be greeted by the game itself, without any kind
of intermediary.  Multiplayer options will be visible on the same page.

we'll need to:
* Implement a MongoDB/Express backend to track states *(eg names, high scores)*
* Create a playable game
* Connect multiplayer sessions

## Functionality and MVP

 - [ ] Track games and players.  User creates a game and another can join.
 - [ ] Game can be played single player
 - [ ] Game can be played multiplayer
 - [ ] Front end is designed to suit needs


## Technologies and Technical Challenges
**dr-react-mario** is a React driven web game that utilizes **MongoDB** to persist
relevant information and **Socket.io** to connect players.

##### Backend: MongoDB/Express

##### Frontend: React/Node.js, Socket.io

The two main challenges we'll need to overcome are implementing the implementing the
basic game and establishing connectivity with Socket.io.

##### Basic Game
Efficiency of code and logic and size of the workload are the main challenges here.  The game will be constantly re-calculating and re-rendering an 8 x 20 two-dimensional array of components.

* Renders the game prepopulated game board
* Continuously drops pills until the game is over
* Implements the 'four in a row' and 'remaining pill half drops' logic
* Key presses move the active pill left, right, and rotated.
* Game is over when all viruses are elminated or pills are stacked too high

##### Mutiplayer Game
While the list here seems smaller, most Socket.io information available is for JavaScript games.  We'll need to both
learn a new technology and implement it in a non-traditional way.
* Users can create and join a game.
* Users alternate turns, controlling every other pill that drops.
* Game state needs to be identical on each player's computer. 


## Group Members and Work Breakdown
**Rushil Vig, Robert Hubert, Chaitanya Desai, Marc Schlossberg**

##### Things Accomplished Over the Weekend



## Proposal must have a day-by-day breakdown for each individual. See sample proposal for clarification.