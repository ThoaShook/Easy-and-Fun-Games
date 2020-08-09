##### Easy-and-Fun-Games


###### Rock, Paper,Scissors Game:


![](images/rock_scissors_paper_Image.png)


* In this game, I make a one-player Rock, Paper, and Scissors Game that requires the player input 
    (rock,paper, scissors) and a automated player (computer randomly automate generated input (rock,paper, scissors).
    Compare them, print out a message of congratulation to the winer, and ask if the player want to start a new game.

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
    1.Welcome player! Let's play the Rock-Paper-Scissors game!
    2.The rules are: 
        rock beats scissors,
        scissors beats paper,
        paper beats rock.
    3.The computer randomly generates rock, paper, or scissors.
                      You enter your choice.
                      You win or lose based on the game rules.
    4. Please type 'q' to exit.

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