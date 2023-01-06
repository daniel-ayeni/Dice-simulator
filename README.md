# Dice-simulator
This code is a simple dice rolling simulator. 
The game generates two random integers between 1 and 6, simulating the rolling of two six-sided dice, and prints the values. 
The game then prompts the user to input whether they want to roll the dice again, and the game continues until the user inputs a value other than "yes" or "y".
The code begins by importing the random module and defining the minimum and maximum values that can be rolled on the dice (1 and 6, respectively). 
It also defines the roll_again variable, which is used to control the loop, and initializes it to "yes". 
The game is then played in a loop that continues until the roll_again variable is set to a value other than "yes" or "y".
Inside the loop, the code uses the random.randint function to generate two random integers between 1 and 6 and prints them. 
It then prompts the user to input whether they want to roll the dice again and stores the input in the roll_again variable. 
If the user inputs "yes" or "y", the loop continues, and the game rolls the dice again. 
If the user inputs any other value, the loop is exited and the game ends.