# Versus, An Interactive HCI Game

## Installation

How to run the project:
This code has no outside dependencies as it relies on built-in JS libraries and does not use any back-end technology.<br>
To start the game, open the `start.html` file in a new browser window. The game should start shortly after. 

## Brief description of the project:

Versus is a game that displays a poll between two options, and the user can choose which one they want to vote for. Following voting, the participants can view the current number of votes for both options and which one is in the lead. The display then gives an option for the participant to fill out a Google form with a new question that could be used in a future Versus game.


## Tasks the installation addresses:
Users can engage in non-taxing physical activity
Users are required to raise their hands (in some cases, for a duration of 5 seconds) to move on to the next slides or make their choice and move out of the frame to end the game. 
Users can engage with other students by making their own responses through a google form, as well as seeing how others responded on a scoreboard.

Constraints from the deployment environment:
Our game ends/exits when the user leaves the frame, so users should stand relatively close to the screen if they want to play. 

## Collaboration record:

Freeman Irabaruta (fni2): Created the forked GH repository; implemented the counter function; Created the initial version of the QR code page and created the google form; tested various user prototypes over the past week.  

Annette Lee (adl55): Implemented the start.html, new qr.html, and vote.html pages. Created the logic for counting the number of hands raised in front of the screen (ex: multiple people’s hands raised, more than one hand raised) and displayed the corresponding error messages. Helped with the updated google form and UI. Tested various user prototypes.

Seema Patil (skp42): Added localStorage variables in order to be able to pass down voting tally data from one html page to another and coded the updating of these values, updated qr code and form, helped with timer bugs, implemented switching between html pages, implemented score.html (bar chart and text display). Tested various user prototypes.
