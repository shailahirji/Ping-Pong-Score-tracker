# Ping-Pong-Score-tracker
Arduino 101 based Ping Pong Score tracker 

Description

The Arduino was programmed using C. 

Implementations of the accessory:
-Player 1 starts first. 
-The match rule setting is set to best of five games.
-To win a match, a player must get 11 points. If the players are at a tie score of 10 or more, the game will continue until someone wins by a two point margin.
-The server changes every 2 points. However, if the score is 10 or more, the server changes every one point.
-As the players switch sides between each set, their respective scores will also switch sides on the LCD. 
-After every set, the winner of that set will begin the next set. 
-At the end of the game, the winner's name will appear on the LCD as "Player 1" or "Player 2" and their respective LED will flash 