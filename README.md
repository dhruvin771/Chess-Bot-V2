# Unity Chess Bot V2 - [Work in Progress]

A 2D chess game with a smart AI opponent. The AI gets better over time by learning from grandmaster-level games. The bot is still a work in progress.

![Chess](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/c04dcc5f-bd8a-47f7-bcf7-835afc347ce8)

## How it Works
The cloned game follows typical chess rules on an 8x8 grid. You can play as white or black and can choose between Player vs Player, Player vs AI, or AI vs AI modes. The bot analyzes future moves to decide the best possible move.

## Depth of Search
The bot searches for moves up to a certain depth in the game tree. A deeper search allows for a more thorough evaluation of potential moves but also requires more computational resources.

![chess-shannon-type-a](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/64f2de0d-30b9-4b2b-aaa3-95b18e75dbc8)

## Alpha-Beta Pruning
To optimize the search process, the bot uses alpha-beta pruning. This technique reduces the number of nodes evaluated in the search tree by eliminating branches that are unlikely to affect the final decision.

![1_96QEzhnsOkNqz7swB0qx8w](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/7d7b8684-0956-476d-b3c5-0b8cfa4862ef)

## Chess Rules
The algorithm ensures that all generated moves adhere to standard chess rules, including legal piece movements, castling, en passant captures, and pawn promotions.

![Ajedrez_captura_al_paso_del_peon](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/29e61f3f-a39f-4677-a112-96e8cccfc71a)

## Future Improvements
I am currently working on enhancing the bot's capabilities to create a more powerful AI. This involves training the bot using grandmaster-level PGNs (Portable Game Notation) to improve its decision-making process and overall gameplay strength.

## Credits
This project is a forked. The main source of inspiration and learning for this project comes from [this video](https://www.youtube.com/watch?v=U4ogK0MIzqk&t). 

Stay tuned for more updates as the bot continues to evolve!