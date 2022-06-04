## Chess in React
Combined chessboard and chess backend. Everything should be modeled except for certain extreme edge cases. The 50-move-rule and threefold-repetition are both tracked, but certain draws by insufficient material are not tracked. Specifically, the following draws by insufficient material are tracked:
```
    king against king;
    king against king and bishop;
    king against king and knight;
    king and bishop against king and bishop, with both bishops on squares of the same color (see King and two bishops).
 ```

In the future, commands will be executed in accordance with the Universal Chess Interface (UCI) specifications. 
