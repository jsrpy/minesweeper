## Little Minesweeper
This contains a little minesweeper written in nodejs, playable on your local machine's command line, with nodejs installed.

### ES6 & ES5
Source code under [src](src) is written in ES6. Whereas those under [lib](lib) is transpiled to ES5 using Babel.

### Main Components
The Board and Game classes are stored in their js files respectively.

### How to Play
To play Minesweeper, we will create instances of MineSweeperGame in command line.

For example:
1. In the command line, navigate to the lib directory and run `node`
2. Run `.load game.js` to load the contents of this file.
3. Then create a Game instance and run commands like so:
4. `let game = new Game(3, 3, 3);`
5. `game.playMove(0, 1);`
6. `game.playMove(1, 2);`
7. When done run `.exit`

### Features

1. Custome board size and number of bombs.

More features to be added soon...!
