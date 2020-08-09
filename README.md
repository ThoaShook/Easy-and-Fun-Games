##### Easy-and-Fun-Games


##### Rock, Paper,Scissors Game:


![](images/rock_scissors_paper_Image.png)


    * In this game, I make a one-player Rock, Paper, and Scissors Game that requires the player input (rock,paper, scissors) and a automated player (computer randomly automate generated input (rock,paper, scissors).Compare them, print out a message of congratulation to the winer, and ask if the player want to start a new game.

    * The rules are: rock beats scissors, scissors beats paper, and paper beats rock.

    * Procedure:
        1. Print out the welcome line
        2. Explain the game rules
        3. Prompt the player to type 'q' if he/she want to exit the game
        4. Import 'random' library
        5. Create a while loop
        6. Generate random auto-input (rock, scissors, paper)
        7. Enter the player-input
        8. Create conditions based on the game rules (in order to win/lose the game)
        9. Prompt the player re-enter the input if necessary (misspell,...)

    * Below are the outcomes of the game:
        * 1.Welcome player! Let's play the Rock-Paper-Scissors game!
        * 2.The rules are: 
            * rock beats scissors,
            * scissors beats paper,
            * paper beats rock.
    * 3.Steps: 
            * The computer randomly generates rock, paper, or scissors.
            * You enter your choice.
            * You win or lose based on the game rules.
    * 4. Please type 'q' to exit.

        Player_Input: rock
        Computer: ['scissors']
        Congrats! You win.
        Player_Input: scissors
        Computer: ['paper']
        Congrats! You win.
        Player_Input: paper
        Computer: ['rock']
        Congrats! You win.
        Player_Input: paper
        Computer: ['scissors']
        Sorry! You lose.
        Player_Input: rock
        Computer: ['scissors']
        Congrats! You win.
        Player_Input: rock
        Computer: ['paper']
        Sorry! You lose.
        Player_Input: rk
        Computer: ['paper']
        Invalid input. Please try again.
        Player_Input: q
        
        
##### CowBull Game


![](images/cowsbullsGame.png)


    * In this game, I create a program that plays the “cows and bulls” game with the user. The game works like this:
    * Randomly generate a 4-digit number. Ask the user to guess a 4-digit number. For every digit that the user guessed correctly in the correct place, they have a “cow”. For every digit the user guessed correctly in the wrong place is a “bull.” Every time the user makes a guess, tell them how many “cows” and “bulls” they have. Once the user guesses the correct number, the game is over.
    * Keep track of the number of guesses the user makes throughout the game and tell the user at the end.
    * Procedure:
        1. Create a function named cows_bulls that takes two arguments: an automate generated number and the player's number
        2. Import 'random' library
        3. Print out the welcome introduction, the rules'game, and the condition to exit the game if desired
        4. Create a while loop that iterates through the automate generated number and compare them with the player's input number prompt the winner or loser based on if elif conditions
        5. Prompt the player to re-enter his/her input if the player input isn't an integer number.
        
    * Here is the outcome after running the codes:
        
        * 1. Welcome! Let's play the cowsbulls game!
        * 2. The machine'll generate a 4 digits number, and your job is to guess that number.
        * 3. For every right digit you guess in the right place, you have a cow. 
               If a right digit at a wrong place, you have a bull.
               If you have 4 cows, you win!
        * Type 'q' to exit.

            Enter your number: 1000
            You have 2 cows, and 2 bulls.
            Your guess isn't right, please try again.
            Enter your number: 1023
            You have 3 cows, and 0 bulls.
            Your guess isn't right, please try again.
            Enter your number: 1024
            You have 2 cows, and 0 bulls.
            Your guess isn't right, please try again.
            Enter your number: 1053
            You have 3 cows, and 0 bulls.
            Your guess isn't right, please try again.
            Enter your number: 1063
            You have 3 cows, and 0 bulls.
            Your guess isn't right, please try again.
            Enter your number: 1073
            You have 4 cows, and 0 bulls.
            You won the game after 6 gueses! The number was 1073.