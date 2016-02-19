MineSweeper  -Adam Ingram

Consists of MineSweeper.java, Game.java, and Board.java

Background:
This is a project I completed for my CS232 class in 2014.
This is a MineSweeper game that is played through the command prompt. 

***How To Play***
1. Make sure all files are saved in the same folder.
2. Open the command prompt to the directory the file is saved in. 
3. Type in 'javac MineSweeper.java' to compile the code.
4. Type in 'java MineSweeper' to run the game.
5. Enjoy your game!

General rules for how to play MineSweeper:
Uncover a mine, and the game ends. Uncover an empty square, and you keep playing. 
Uncover a number, and it tells you how many mines lay hidden in the eight surrounding 
squares—information you use to deduce which nearby squares are safe to click.

Code API:
MineSweeper.java
    - Class used for initializing a new game
Game.java
    - Class used for directing gameplay   
    - Included method:
        Play(Board)
            Play is a public method that takes a Board object and manages turns, as well as 
            handles displaying if the player has won or lost.
Board.java
    - Class used for setting up the game board as well as establishing the game's logic
    - Included methods:
        win()
            Public method that takes no arguments and returns a boolean. 
            Determines if the game has been won.
        getPosition(int, int)  
            Public method that returns the position specified at a certain line and column
        setPosition()
            Public method that takes no arguments and returns a boolean.
            Prompts user for input and determines if move is valid.
        show()
            Public method that takes no arguments.
            Displays the board.
        startBoard()
            Public method that takes no arguments.
            Initializes the board.
        randomMines()
            Public method that takes no arguments.
            Generates random mine placement.
    



