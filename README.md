# Set_Card_Game
Set card game developed with pygame
 Dear SET player, 

SET is a card game with a total of 81 cards, each with a number of symbols with a certain color and filling, where the player 
has to find a SET from a group of 12 cards. The cards therefore each have 4 properties: The number of symbols (1,2 or 3), the shape of the 
symbol (circle, tilde or diamond), the color of the symbol (red, purple or green) and the filling of the symbol (filled, empty, or 
dashed). A SET is a combination of 3 cards, in which the properties of the cards per property are either all three the same or 
all three are different. For example, a SET would be: One red empty diamond, two red empty tildes and three red empty circles. 
The color and fill remain the same, while the shape and number differ.

The game starts with a pile of 81 cards (all possible combinations) and 12 of these are placed on the table (the screen), and 
numbered. The player and the computer have 30 seconds to find a SET in these 12 cards. When the player finds a SET, 
he/she enters it using the input bar at the bottom of the screen, entering the numbers of the cards separated by a comma. 
Don't forget to click the bar with the left mouse button first, to "turn it on".

If the player finds a SET within 30 seconds, the player gets a point, the 3 SET cards are replaced by 3 new cards from
the deck. If the player has not found a SET after 30 seconds, and there is a SET on the table, the computer gets a point and
the SET cards are replaced by 3 new cards from the deck. If there is no SET on the table, nobody gets a point and
after 30 seconds the first 3 cards are replaced by 3 new cards from the deck.
The moment the pile is used up, the game is over and whoever has the most points wins!

How to start the game:
1. To play the game, the player must first install pygame. If you already have pygame installed, proceed to step 2.
Install as follows: In Anaconda Navigator, launch the application CMD.exe Prompt.
Type in the sentence: py -m pip install -U pygame==1.9.6 --user , and press enter. Now pygame will be installed.
Another method to install pygame is to install Python from Microsoft Store or Apple Store and then run the
"Command Prompt" or "CMD" program on your computer. Now type the same sentence: py -m pip install -U pygame==1.9.6 --user in the terminal and
press enter.
2. If pygame is successfully installed, open the setgame.py file, located in the same folder as this .txt file, in Spyder.
3. Then press "F5" or the green arrow at the top of the screen and the game will start. If you get an error called 
"No module named 'pygame'", pygame was not installed successfully. So go back to step 1. 
4. To start the game, click anywhere on the screen. The game has now started. 
5. To enter a SET, turn on the input bar by clicking on it and enter the numbers of the SET cards separated by 
commas (eg 8,10,12).
