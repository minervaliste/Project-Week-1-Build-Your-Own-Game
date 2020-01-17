<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Master Mind
*[Minerva Liste]*

*[DALF, IronHack BCN & 17/01/2020]*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

Mastermind is a code-breaking game for two players invented in 1970 by Mordecai Meirowitz, an Israeli postmaster and telecommunications expert. It is inspired in an earlier pencil and paper game called Bulls and Cows.

A fast and simple strategy game, addictive to play when you are into deductive reasoning and logic!


## Rules

- The aim of the game is to guess a pattern of elements (master code combination) that is chosen at the beggining of the game.

- The length of the pattern, the variety of elements that can form the pattern and the number of turns available to guess the pattern may be agreed at the begginnig of the game. For this version, a pattern of 4 integrer numbers ranging from 1 to 6 has been set. The number of turns allowed is 12.

- In each turn, the player tries to guess the pattern by entering a possible code combination. 

- Feedback is provided next to the combination by showing a (x) for each element of the code matching the exact same element on the same position on the master code combination, and a (o) for each element existing in the master color combination but placed in the wrong position.

- If there are duplicate elements in the guess, they will only be awarded with feedback symbols if they correspond to the same number of duplicate colours in the master code combination. For example, if the master code combination is ['1', '1', '2', '2'] and the player guesses ['1', '1', '1', '2'], he will be awarded two (o) for the two correct '1', nothing for the third '1' as there is not a third '1' in the master code, and a third (o) for the '2'. 

- Once feedback is provided, another guess is made. Guesses and feedback continue until either the player guesses correctly or the number of turns is over. 


## Workflow

The steps considered to code the program where:

- Create a function that randomly chooses a code combination.
- Create a function that requests the input of a code combination to the player.
- Create a function that checks and validates the code combination of the player.
- Create a function that compares code combinations.
- Create the game workflow (choose master code combination, ask player to guess code, compare guess code to master code, provide feedback, control number of rounds, control conditions for winning or loosing the game)

## Organization

Prior to the design and development of the program, an initial project planning was set on Trello. After documentation and design, this planning was altered to include the different development tasks defined during the design stage. The Kanban board used can be seen below in the Links section. 

Since no external links or resources where used for the development of the game, the file structure of the repository is very simple, with a single folder (/your_project) including the main Jupyter Notebook file (Mastermind.ipynb) and the readme file (README.md).

## Links

[Repository](https://github.com/minervaliste/Project-Week-1-Build-Your-Own-Game)  
[Slides](https://drive.google.com/open?id=1oVoBqhv2qSOb9tYDAhn40cPKZgyoAesF0ImyzXNt1CI)  
[Trello](https://trello.com/b/xfyPtizj/project-1-mastermind-game)  
