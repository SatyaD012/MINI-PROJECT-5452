Overview:  
This is a simple Number Guessing Game written in C. The goal of the game is for the user to guess a randomly generated number between 1 and 100. The program provides feedback on whether the guess is too high, too low, or correct, and tracks the number of attempts made by the user.

FEATURES:  
The program generates a random number between 1 and 100.
The user is prompted to input a guess.
After each guess, the program provides feedback on whether the guess is too high, too low, or correct.
The program counts the number of attempts and displays it once the user guesses the correct number.

Requirements:  
To run the program, you need:  
1. A C compiler (e.g., GCC)
2. A terminal or command-line interface to run the executable

How it Works:  
The program uses srand(time(0)) to generate a different random number each time. It prompts the user to guess a number between 1 and 100, providing feedback ("Too high!", "Too low!", or "Correct!") until the correct guess is made, along with the attempt count

OUTPUT:  
Welcome to the Number Guessing Game!  
Guess the number between 1 and 100  
Enter your guess: 50  
Too high! Try again.  
Enter your guess: 30  
Too low! Try again.  
Enter your guess: 40  
Congratulations! You guessed the number in 3 attempts.  
