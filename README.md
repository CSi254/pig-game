
# _Pig Dice Game_

# Author
John Gatheru

## Description

_This web application allows two players to play a game of Pig Dice._

## Specs
| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Player 1 clicks ROLL button | Click ROLL button | Dice rolls and number is generated |
| If Player 1 rolls any number other than 1, that roll is added to round total | Roll = 2 | Round total = 2 |
| If Player 1 rolls a 1, no score is added and round for Player 1 ends | Roll = 1 | Round total = 2 / Total score = 2 / Player 2 begins |
| Repeat for Player 2 | Roll = 1 | Round total = 0 / Total score = 0 / Player 1 begins |
| When a player's total score reaches 100 or more, game ends and winner alert popup shows | Player 1 total score = 100 | Winner alert pop up |


## Setup/Installation Requirements

* _Clone this repository_
* _Open a HTML file_
* _Open web browser of choice_


# GAME RULES:

- The game has 2 players, playing in rounds
- In each turn, a player rolls a dice as many times as he whishes. Each result get added to his ROUND score
- BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
- The player can choose to 'Hold', which means that his ROUND score gets added to his GLBAL score. After that, it's the next player's turn
- The first player to reach 100 points on GLOBAL score wins the game


# link to live page
https://csi254.github.io/pig-game/


## Technologies Used

* _HTML_
* _CSS_
* _Bootstrap_
* _JavaScript_ 
* _jQuery_

# support and contact details

Contact the author at: johngatheru18@gmail.com



### License
















