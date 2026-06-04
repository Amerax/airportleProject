# airportleProject
A fun wordle type game except with airport codes. 


To play the game simply open up any IDE and insert both the .csv file and the .py python file. Then simply run the code and follow the instructions on the terminal!

Demo link w/ NO DOWNLOAD REQUIRED simply press run on the top right: https://py3.codeskulptor.org/#user311_7xHy7xPOqT_0.py

REMINDER: YOU MUST type 3 letters at once to play the game properly, not just one letter at once like with hangman. So you must input "abc" "xyz" NOT just "x" then "y" like that. 

This code was written in python. 

The game operates using a continuous feedback loop divided into three main parts: picking a code, running the menu, and evaluating guesses. First, the program sets up a collection of three-letter airport codes and uses a random number generator to select one secret target for the round. A main menu loop manages the user's entry into the game, ensuring that once a match ends, the player is cleanly prompted to play again rather than the script shutting down.

Inside the core game engine, the program tracks the match state using counters for your remaining turns alongside lists that sort your guessed letters into correct spots, wrong spots, or wrong letters entirely. During each turn, the script checks if your input is exactly three letters long to increment your turn counter, and then simultaneously evaluates the character and its position index against the secret code. If you match the code exactly, you win; if you hit six valid attempts without a match, the loop terminates and reveals the correct airport code.
