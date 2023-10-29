<h1 align="center">Connect 4</h1>
## How it works?
The main algorithm used for this project is a depth limited <a href="https://en.wikipedia.org/wiki/Minimax">minimax algorithm</a>. To put in to layman's terms, the algorithm creates a search tree given the state of the board, for all possible moves that it could make, it then repeats this process for (a depth of) 5 times, at which point it will try to determine the best move out of all possible moves and then play it.
