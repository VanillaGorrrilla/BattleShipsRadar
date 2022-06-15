# BattleShipsRadar
The basis of the game is a 10 by 10 board that carries a variety of different sized ships that will be randomly placed on the board by the computer. It is the user objective to try and sink all the ships and beat their score by inputing the desired co-ordiinates on where they want to shoot. With my variation of battleships, I added a radar that the player can place on the board that will scan a 1 square area around the radar and highlight any ships that it finds. 

# Requirement Specification:

•	10 by 10 board

•	Aircraft Carrier: 5 squares long 

•	Battleship: 4 squares long 

•	Submarine: 3 squares long 

•	Destroyer: 3 squares long 

•	Patrol Boat: 2 squares long

•	Computer should randomly place the ships on the board

•	Ship sinks when all squares have been hit

•	Player should enter the X and Y coordinates of a shot

•	Computer should display the appropriate message after the shot, either:

o	My ship was hit!

o	You missed!

o	You sank my [ship type]!

•	List of the sunk and un-sunk ships should be displayed (constantly updating)

•	The board should be visible to the player but not the ships

•	The board should be updated with the after each shot, the chosen square is updated by adding an ‘M’ for Miss and ‘H’ for Hit

•	Keep a running score for the player during the game

o	Score starts at 0

o	Each shot deducts a point from the score

o	Each hit adds a point

o	After a ship has sunk, the number of points is equal to the length multiplied by 2

•	Game ends after the player sunk all ships or they quit

•	At the end of the game it should display the score of the player and ask if they want to play again

•	4 radars that the player can use throughout the game. It can detect a ship that is 1 square away from the radar position


# Future Improvements
I would like to have the map on the GUI instead of the console. This will make the game look more professionally done and finished but due to my limited understanding of Swing i was unable to do so.
