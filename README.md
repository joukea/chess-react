## Chess in React
This is a small prorgram I've written extending the react tutorial. Boards are set up using Forsyth–Edwards Notation, and moves are recorded with algebraic notation. This program contains both a chess frontend and backend. Everything should be modeled except for certain extreme edge cases. The 50-move-rule and threefold-repetition are both tracked, but certain draws by insufficient material are not tracked. Specifically, the following draws by insufficient material are tracked:
```
    king against king;
    king against king and bishop;
    king against king and knight;
    king and bishop against king and bishop, with both bishops on squares of the same color (see King and two bishops).
 ```
[More complex drawn endgames, such as blocked king and pawn endgames, are not modeled as they would require a much more complicated evaluation function.](https://www.chessprogramming.org/Draw_Evaluation)


In the future, commands will be executed in accordance with the Universal Chess Interface (UCI) specifications. 
