# Rock Paper Scissors Game (Python)

A simple command-line Rock Paper Scissors game built using Python and NumPy. The player competes against the computer for a specified number of rounds, and scores are tracked throughout the game.

## Features

* Play Rock, Paper, Scissors against the computer
* Random computer choices using NumPy
* Score tracking for both player and computer
* Multiple rounds support
* Displays the winner after each round

## Technologies Used

* Python 3
* NumPy


## How to Run

Run the Python script:

```bash
python rock_paper_scissors.py
```

Enter the number of rounds when prompted and choose one of the following options each round:

* stone
* paper
* scissor

Example:

```text
enter no of rounds: 3

choose stone,paper or scissor stone
player wins

choose stone,paper or scissor paper
draw

choose stone,paper or scissor scissor
computer wins
```

## Game Rules

* Stone beats Scissor
* Scissor beats Paper
* Paper beats Stone
* If both player and computer choose the same option, the round is a draw.

## Future Improvements

* Input validation for incorrect choices
* Display computer's choice each round
* Declare the overall winner after all rounds are completed
* Option to replay the game
* Improved code structure using dictionaries or classes

## Project Structure

```text
rock-paper-scissors-python/
│
├── rock_paper_scissors.py
└── README.md
```

## Author

Gauransh

Feel free to fork this repository, submit improvements, and use it for learning Python fundamentals.
