* Games
  * [Uno](https://github.com/Travis-Findley/Uno)
    * Uno 2-4 players online eventualy, normal and flip, with AI.
  * [Random Number Guesser](https://github.com/Travis-Findley/RandomNumbGuess)
    * Guess the random number
  * [Dice Role](https://github.com/Travis-Findley/DiceRole/blob/main/README.md)
    * It roles a die
  * [Change Making Game](https://github.com/Travis-Findley/ChangeGame)
    * Play a game for making Change up to 1 doller
  * [Joke Teller](https://github.com/Travis-Findley/JokeTeller)
    * This tells a joke when user clicks a button
  

```mermaid
graph TD;
    A[Finish Uno] --> B{Make Form};
    B --> |0.0.2.0| C{Auto Update};
    C --> |`.`.`.`|D[Add Games Games];

    D --> E{C# Class};
    E --> F(Uno);
    E --> G(Random Number Guesser);
    E --> H(Change Making Game);
    E --> I(Joke Teller);
    E --> J(Dice Role);

    D --> K{Python};
    K --> L(MadLib);
    K --> M(Wordle);
    K --> N(Wheel Of Fortune);
    K --> O(Choose Your Own Adventure);
    K --> |Add python fetures to C# project| G;
    K --> P(Coin Flip);
    K --> Q(Rock Paper Scissors);
    K --> R(War);


    L --> X;
    M --> X;
    N --> X;
    O --> X;
    P --> X;
    Q --> X;
    R --> X;
    X{Port to c#} --> Z

    F --> Z;
    G --> Z;
    H --> Z;
    I --> Z;
    J --> Z[Done];
```
