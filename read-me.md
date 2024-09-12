# Connect 4 Project Planning

![Screen shot showing wire frame design for connect four game](./Assets/Screenshot%202024-09-12%20121500.png)

## Connect Four User Story
- Game to initialise when page loads
- Clear heading showing that this is a connect four game
- Instructions displayed how to start the game and play the game
- Clean unbusy design
- Simple animation to make the user experience better/more interesting
- Clear/conventional user interface e.g. click on the collumn you want to drop your coin
- Clear indication of whose turn it is "Red" or "Yellow"
- Be notified when the game is over
- Be notified which colour won the game
- Also show the winning set of four so it's clear to see what the winning move was
- Option to play again
- Score counter to keep track of wins and losses in this session
- Option to reset/reload page

## Pseudocode

1. App initialises on page load
2. Define any variables used to track the state of the game
> * Yellow choice
> * Red choice
> * turn
> * win
> * draw
> * resultCounter
> * gameOver

3. Constants
> * Grid (2D array)
> * Dom elements for displaying messages
>> * turn
>> * winner

4. Handle Player Clicking button
> * each column button to drop coin
> * play again
> * reset score

5. Functions
> * Initialise
> * Render
> * Update board
> * Switch player
> * Place peice
> * Update score
> * Click handlers
> * Check connect 4
> * Dissplay winner



