Number Guessing System


 1. PROJECT OVERVIEW


This is the number guessing system in which computer will pick a random number and the player has to guess the number.


The player has three options to choose the level of game: Easy, Medium and Hard. Depending on the level selected, the range of number will change. After every attempt, the program will indicate whether the guessed number is too high or low.


The program will also keep track of the number of attempts and score. The player can play another round and the best score will be saved in the game.


This project has been built to practice the basic python concepts like functions, loops, conditions, input and exception handling from the user, random module to pick random numbers.


2. FEATURES


Some of the key features of this project are as follows:


- Shows a welcome message


- Asks the user to select the difficulty level


- There are three options for the difficulty level:


- Easy (range 1-50)


- Medium (range 1-100)


- Hard (range 1-200)


- Ask the user to enter a guess


- Validate the guess with the range selected


- Provide hints if the guess is too low or high


- Keep track of the number of attempts


- Calculate score based on the number of attempts


- Store and display best score


- Lets the player to play another round


- Shows a thank you message when the player leaves



3. TECHNOLOGIES AND TOOLS


This project has been developed using:


 Programming Language

- Python 3


Module

- random (used to pick the random number for the game)

 Tools


- Google colab or Python IDLE or VS Code


- GitHub (used for storing and sharing the project)


This project doesn't require any other libraries.



 4. PROJECT STRUCTURE


The project structure will be:



Python-utility-for-number-guessing-game
│
├── Python_utility_for_number_guessing.ipynb
├── README.md
└── statement.md

.ipynb contains the python program and README.md , statement.md contains the project details.



5. HOW THE PROGRAM RUNS


The first thing the program will do is show a welcome message and ask the player to select the difficulty level.


The selected difficulty level will determine the range of the numbers. For example, if the player selects easy mode, the computer will pick a number between 1-50.


The player will enter their guess, and the program will compare the guess with the secret number.


If the guess is lower than the secret number, it will print "Too Low".


If the guess is higher, it will print "Too High".


If the guess is right, the player will win.


The number of attempts will decide the player's score. The fewer the attempts, the higher will be the score.


After one round is finished, the player can choose to play again.



6. FUNCTIONS USED


The program is divided into different functions so that each part of the program can be separately handled. The functions used are:


welcome_message()


This function prints the title and a little intro of our program.


choose_difficulty()


This function asks the user to choose between Easy, Medium or Hard and returns the max limit for the range depending on the selected difficulty.


get_guess(maximum)


This function takes the player's guess as an input and validates if the input is in the selected range.


calculate_score(attempts)


This function calculates the score depending on the number of attempts.


play_game()


This is the main function which handles the whole process of picking the number and comparing the input with it.


7. STEPS TO INSTALL AND RUN THE PROJECT


Step 1: Install Python



If it is not installed yet, download and install Python 3 in your computer.



Step 2: Download or clone the project



Download the project from git hub, or clone the project in your local machine.



Step 3: Open the project



Open the project in VS Code or IDLE.



Step 4: Run the program



Open main.py and run the program.



The program will show:



========================================



NUMBER GUESSING SYSTEM



========================================



TRY TO GUESS THE NUMBER SELECTED BY THE COMPUTER.



Now, the player can choose the difficulty option and start playing.



8. Instructions for Testing



The following test cases can be used to check if the program is working correctly.



Test Case Input Expected Result



1 Difficulty = 1 Easy mode with range 1-50



2 Difficulty = 2 Medium mode with range 1-100



3 Difficulty = 3 Hard mode with range 1-200



4 Invalid difficulty such as 5 Program asks for a valid choice



5 Guess smaller than secret number Displays "Too Low"



6 Guess greater than secret number Displays "Too High"



7 Correct guess Displays congratulations and score



8 Guess outside the selected range Asks the player to enter a valid number



9 Play again = yes Starts a new game



10 Play again = no Ends the game and displays the best score



9. SAMPLE OUTPUT



The sample output will look like:



========================================



NUMBER GUESSING SYSTEM



========================================



TRY TO GUESS THE NUMBER SELECTED BY THE COMPUTER.



Choose Difficulty level:



1. Easy (1-50)



2. Medium (1-100)



3. Hard (1-200)



Enter your choice(1/2/3): 1



I have selected a number between 1 and 50



Start guessing:



Enter your guess: 20



Too Low! Try a higher number:



Enter your guess: 35



Too High! Try a lower number:



Enter your guess: 28



Congratulations!



You guessed the correct number



Number of attempts: 3



Your score: 80



Do you want to play again? (yes/no): no



========================================



Thankyou for playing!



Your best score was: 80



========================================




 10. LEARNING OUTCOMES



With this project, I practiced some of the basic python concepts like variables and data types, taking input from the user, if, elif and else statements, while loop, functions, returning values from a function, random module to pick random numbers, Exception handling, basic score calculation, breaking a program in different functions, etc.


I also learned how to combine different functions to make a complete python application.



11. CONCLUSION


The Number Guessing System is a small program built to practice some of the basic python concepts. The game lets the user to choose the level, provides hints, keeps track of the number of attempts, and calculates the score.


I learned how functions, loops, conditions, input validation, exception handling, and random numbers all come together to build this small game. There are many ways to improve and build upon this game, such as adding more levels or a timer.
