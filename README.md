
The objective of this exercise is to gage your proficiency level in programming.

PLEASE READ ALL INSTRUCTIONS
----------------------------

Objective A - To be delivered after 24 hours
-----------------------------------
You will be asked to build a srabble anagramer:

* randomly pick 7 letters from a total set of 102 letters

* find the words in the french dictionnary that maximizes the number of points.

Hints: you do not necessarily need to use all seven letters

Objective B - To be delivered after 48 hours
--------------------------------------------
You will be asked to simulate a simple scrabble game of 2 players without placing the letters on the board.

* each player picks 7 letters in the beginning
* each player uses the anagramer built in objective A to pick the best possible word
* after each round:
  the score is maintained
  players pick additional letters
* handle the flow of the game till the end


Objective C - To be delivered after 72 hours
--------------------------------------------
* same as objective C with the additional difficulty of placing the letters on a scrabble board and accurately calculate the score based on the board.

Objective D - To be delivered after 96 hours
--------------------------------------------
* design a system that can accomodate up to 4 players
* devise a solution that allows the anagrammer to run much faster using caching.
* Design an API for the different methods to make this web friendly.


Instructions
------------
Please code using python 3.7
If you are an entry level software engineer or intern you will need to deliver  Objective A within 24 hours
If you are a software engineer to deliver Objective A+B within 48 hours
If you are a senior software and above engineer you will need to deliver objectives A+B+C+D after 96 hours 

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



Supporting Elements  
-------------------

In this repo you will find the following files to get you started:

- francais.text --> is a helper file that contains all of the words in the french language
- french_scrabble_distribution_with_points.csv --> contains the number of letters in a typical scrabble game and how many points each one conveys.

References:
https://en.wikipedia.org/wiki/Scrabble_letter_distributions#French
https://aide-scrabble.fr/regles/
Scrabble board: https://i.stack.imgur.com/0kZO8.jpg


 
