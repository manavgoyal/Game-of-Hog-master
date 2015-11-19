Hog_Project
===========
This is a CS61A class project assigned by professor John DeNero in Fall '13.

In this project, I developed a simulator and multiple strategies for the dice game Hog. Mastery in the use of control and high-order functions in Python was the goal of this project. 

In Hog, two players alternate turns trying to reach 100 points first. On each turn, the current player chooses some number of dice to roll, up to 10. Her turn score is the sum of the dice outcomes, unless any of the dice come up a 1, in which case the score for her turn is only 1 point. Of course, there are multiple other rules that outline the gameplay and the list of the rules can be found on the linked webpage.

Tkinter, Python's main graphics library, is used to render the graphics. This is the basis for the simulator for the game. Finally, I experimented with ways to improve upon the strategy to have the highest chance of winning the game against the computer. Always rolling a fixed number of dice vs determing the number of rolls (1 to 10) that gives the maximum average score for a turn, were some of the implementations. 
