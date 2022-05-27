# Pacman-Game
Pacman Game with changing maps
Pacman has 3 lives, for all screens,after every win the pacman 
moves to the next board.

The game able to load and save your files
there are 3 modes to the game you can change by changing the Command Arguments as follows.

-load  -the  game loads the last game and you get a reply of the game.

-save  -you play the game and the game is recorded.

-load -silent - the mode is for testing the game run without printing to screen and just testing 
that the actual result corresponds to the expected result, with a proper output to screen (test failed / passed)

#######################################################################################
The game would look for files in the working directory, with the names pacman_*.
screen these files would be loaded in lexicographical order .
so you are welcome to load your own maps.

if you are intersted in loading your own maps this is the requirements:

The screen file should be a text file representing the screen, with:
@ - for the position of the pacman (1 and only)
$ - for the initial position of the ghosts (allow any number between 0 to 4)
# - for walls
% - for “empty” positions that should not have a breadcrumb
& - for the position where the points and remaining lives information (“legend”) shall be presented,
it is the responsibility of the screen designer to make sure that the & is placed in a position not accessible by the creatures.

#######################################################################################
