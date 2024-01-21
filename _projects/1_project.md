---
layout: page
title: Othello
description: Writing a mental game with C language
img: assets/img/proj1.jpg.jpg
importance: 1
category: fun
related_publications: true
---

How to play:
To begin with, four beads are placed crosswise in the middle of the board as shown. The dark piece starts the game.
Each time two players take turns making a move, each piece must be placed somewhere which surrounds one or more pieces of the opponent
Slow down. Making a move means putting a piece (on behalf of your color) on the board Enclosing one or more opponent's pieces in one
or several directions. As a result of each move, the color of the beads surrounded by color Of course, the beads that come out
The flow of the game is placed between your pieces. They do not change to the color of your pieces, but only pieces. which in the lines of 8
Your moves are placed, they become the color of your pieces.The goal of the game Having the most pieces of the same color on the board
It is the end of the game.
Endgame:
When the whole screen is filled or none of the two sides have moved, the game It ends and the player who has the number of pieces
The one who has more on the game board is the winner.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/proj11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Game timer mode:
When starting a new game, there are two game modes: First, the default mode All the explanations are in the section
is given in advance. The second mode is the timed mode. In the timed mode, every The player has time like 10 minutes.This time
can be entered by the user but should not exceed a certain limit Set the limit as you wish.
When the game starts, the timer for each player's turn starts counting down .every time you make a move
the timer is stopped and the opposite opener's timer starts at the same time as his turn starts Explanations related to the calculation of points
And the effect of the timer on the winner of the game is shown in the previous section.
Note: The remaining time of both players should be displayed, but there is no need to display A Nalin and there is no moment of time in this
For example, consider a command that, by entering it, the remaining time of both The player will be displayed.

