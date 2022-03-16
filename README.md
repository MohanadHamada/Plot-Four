# Plot-Four
>Agent
- The performance measure : the result of the game, win, loss, or tie. The number of moves it takes to win the game doesn’t really matter, so the only thing the agent should care about is results.
- The environment : the game board of Connect 4, a( 6 x 7 )board. 
- This agent’s actuator : making a move in the game.
- The sensors in this situation would be the game board, the agent should know the state of the game board at all times.
>Environment 
- This agent’s environment would be fully observable, as the agent always knows exactly where the pieces are in the game board.(One measure of complexity of the Connect Four game is the number of possible games board positions. For classic Connect Four played on a 7-column-wide, 6-row-high grid, there are 4,531,985,219,092 positions[5] for all game boards populated with 0 to 42 pieces. )
- This is also a multi-agent competitive environment, as there will be two agents playing against each other.
- This environment is deterministic, there is no element of randomness to Connect 4.
- This is a sequential environment, as each move affects the game board going forward, which affects what the possible moves will be in the future.
- There is also a static environment while deciding an action.
- It is also a discrete environment, as there are only ever up to 7 options for a move on a given turn.
>>This agent also has discrete percepts, as it only needs to use its percepts and update the game board after the other agent makes a move. There is a known outcome of actions, you know what your move will do, although you do not know what move the opponent will make.
