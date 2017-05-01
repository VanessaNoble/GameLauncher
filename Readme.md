# The Guessing Game

This Guessing Game involves a 'game' object and three 'player' objects. The game generates a random number between 0 and 9, and the three player objects try to guess it. 

## The Logic:


* The GameLauncher class is where the application starts; it has the main() method.
* In the main() method, a GuessGame object is created, and its startGame() method is called. 
* The GuessGame object's startGame() method is where the entire game plays out. it creates three players, then "thinks" 
of a random number(the target for the players to guess). It then asks each player to guess, checks the result, and either prints out information about the winning player(s) or asks them to guess again. 
 