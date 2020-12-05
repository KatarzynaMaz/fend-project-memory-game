# Memory Game Project

## Table of Contents

* [Instructions](#instructions)
* [Contributing](#contributing)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## Game
The object of this Memory Game was to match 8 pairs of cards as quickly as possible. At the start of the game, the cards were flipped, so the player couudn't see their icons. By cicking on the card, we can open the card. The moment we flip the first card, the timer starts. The first flipped card stays open until the second card clicked on is revealed. Two flips count as one move that a player makes (two cards need to be flipped in order to determine if they match, so two flips count as one move). The star rating is also kept (the longer the player plays, the less stars he gets) Once we have 2 open cards, we check if they match. If they do, they stay open; if they don't, they quickly get fipped back. The time was set after which the cards are flipped over, so we don't memorize the cards. We flip the cards until all are open.  When they all are open, the modal with statistics pops up. The player is giving an option to play again. If he choses to play again, the cards are shuffled, the moves, the timer and the star rating are set as well. And the fun begins again. 

## Dependencies
fonts.googleapis.com/css?family=Coda