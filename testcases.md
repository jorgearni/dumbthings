# TIC TAC TOE 



## The board 
A | B | C
D | E | F 
G | H | I

## Requirements:

Winning conditions: horizontal, vertical, diagonal. When a winning condition is fulfilled a message is desplayed
Match starts by selecting a random player to start the match.
Only 2 players.
Players take turns to fill a box.
Each player has a shape to identify selected boxes in the board. Either X or O 
X shape is assigned to the player that starts a match.


## Test Cases
### Initial conditions
ATTEMPT to start a new game. VERIFY player 1 and player 2 are randomly selectec to start 
ATTEMPT to start a new game. VERIFY all boxes are empty 
ATTEMPT to start a new game. VERIFY that user can select any box 

### Switching from user to user 
ATTEMPT to select any box in the first turn. VERIFY active player is switched

### Different shapes used to identify users 
ATTEMPT to select a box after swithching players´. VERIFY different shapes are used to identify ech player 

### Winning conditions 

[A,B,C],[D,E,F],[G,H,I]
ATTEMPT to enter any horizontal wining condition using any player. VERIFY winning player is displayed
[A,D,G],[B,E,H],[C,F,I]
ATTEMPT to enter any vertical winning condition using any player. VERIFY winning player is displayed   
[A,E,I],[C,E,G]
ATTEMPT to enter any diagonal winning condition using any player. VERIFY winner is displayed


### Blocking conditions and tie 
ATTEMPT to enter a comnbination that leads to Player having a posibility of winning using any horizontal combination and the other blacking blocking the winning move. VERIFY no winner is displayed.

...Vertical 

...Horizontal

ATTEMPT to enter any combination that fills all the board without a winning condition fulfilled. VERIFY match is declared a tie.   
