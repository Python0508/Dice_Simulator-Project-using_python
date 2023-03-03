# Dice_Simulator-Project-using_python
 Create a program that simulates rolling dice and displays the results.
This is a simple Python program that simulates rolling a pair of dice. It uses the random module in Python to generate random numbers between 1 and 6 for each die.

The program starts by defining a function called roll_dice() that generates two random numbers between 1 and 6 for each die and prints out the result. The sum of the two dice is returned by the function.

The next function defined is start_rolling(), which asks the user whether they want to roll the dice again. It uses a while loop to keep asking the user for input until they enter either 'Y' or 'N'. If the user enters 'Y', the function returns True, indicating that the user wants to roll again. If the user enters 'N', the function returns False, indicating that the user does not want to roll again.

The main part of the program uses a while loop to keep rolling the dice and adding up the scores until the user chooses to stop rolling. The total score for each roll is printed out, and then the start_rolling() function is called to ask the user whether they want to roll again. If the user chooses to stop rolling, the while loop is exited and the program prints out a "Thank you for playing" message.

Overall, this program is a simple example of how to use the random module in Python to simulate a game of rolling dice, and how to use functions and loops to structure the logic of the game.
