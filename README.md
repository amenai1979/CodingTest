
The objective of this exercise is to gage your proficiency level in programming.

PLEASE READ ALL INSTRUCTIONS
----------------------------

Supporting Elements  
-------------------

In this repo you will find the following files to get you started:

- francais.text --> is a helper file that contains all of the words in the french language
- french_scrabble_distribution_with_points.csv --> contains the number of letters in a typical scrabble game and how many points each one conveys.

References:
https://en.wikipedia.org/wiki/Scrabble_letter_distributions#French
https://aide-scrabble.fr/regles/
Scrabble board: https://i.stack.imgur.com/0kZO8.jpg

Objective A 
-----------------------------------
You will be asked to build a scrabble anagramer:

* randomly pick 7 letters from a total set of 102 letters

* find the words in the french dictionary that maximizes the number of scrabble points.

Hints: you do not necessarily need to use all seven letters

example :

generate_random_input(letter_set)
AATEFER
find_best('AATEFER')
AFTER, 8

Objective B 
--------------------------------------------
You will be asked to simulate a simple scrabble game of 2 players without placing the letters on the board.

* Each player picks 7 letters in the beginning
* Each player uses the anagramer built in objective A to pick the best possible word
* After each round:
  the score is maintained
  players pick additional letters
* Handle the flow of the game till the end
* Log the actoions taken by each player and the outcome score in a file. 

Bonus Items
--------------------------------------------
* Devise a solution that allows the anagrammer to run much faster using caching.
* Design an RESTFUL API with different methods to make this web friendly.


Instructions
------------
Please code using python
deliver as many objectives within a week. 


How you will be evaluated
-------------------------

Object oriented design capability

Choice of data structures

Error and exception handling

Usability 

Clarity and reusability of the code

Testing and validation

Documentation

Speed of execution