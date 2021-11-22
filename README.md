# Tic-Tac-Toe
The popular game made for me :D

## usage
First, choose a square and click on it, now is the turn of you oponent, keep it up until there is a winner.
Winner: The winner is who have 3 "X" or "O" in line, could be vertical, horizontal o diagonal.

## Installation
You don't need anymore than a browser, I will recomend you use Chrome to have the best experience.

## Description
This is my version of the famous game Tic-Tac-Toe.
The objective was can communicate Parents and Child components, I did this communication using `<Square takeTurn={takeTurn} id={i}></Square>;`
To knows who is the winner I used an array with a set of win combinations.
`const win = [
  // rows
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  // cols
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  // diagonal
  [0, 4, 8],
  [2, 4, 6],
];`

## Support
If you have a questions or comments you can write me at: 

email: <abel.archila@gmail.com>

Linkedin: **[Abel Archila](https://www.linkedin.com/in/abelarchila/)** 

web page: **[Orion Technologies](http://oriontechnologiesgt.com)**

(To open in new tab CTRL+Click on Windows and Linux or CMD+Click on Mac)

## Roadmap
I will add music in this game.

## License Information
**[MIT Lincense](https://opensource.org/licenses/MIT)**
