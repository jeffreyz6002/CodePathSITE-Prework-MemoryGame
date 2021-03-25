# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Junhui Zhang

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/knowing-sandy-corn

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://recordit.co/srBc5yhcCU

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

One challenge that I encountered while creating this submission is logging on to glitch. It doesn’t seem that complicated
but when I first tried to login through github I kept getting a whitescreen on my browser. I had tried a different browser
and different ways to make an account (via Gmail, email) as well but this still resulted in the same problem. In the end
when pressing login or creating an account via a different glitch site, the problem solved itself. In terms of the code
itself, while just looking at the code seemed pretty confusing at first without descriptions, the prework.md helped a lot
in understanding the code given and what was needed to be done in the next step. Out of the code, the most confusing part
was understanding the uses of singleClue() and why it was needed for playClueSequence(). Without the md, I most likely
would have taken longer time doing this prework.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

From my understanding, going into developer tools reveals to the user the HTML of the website and the code that we have
generated for this assignment is an introduction level of the three languages, HTML, Javascript and CSS. Comparing the
code for this project with popular public domains, why are certain ids and names just made of random numbers and letters?
How long does it take to create a website? Assuming that websites are made by a group of people, without specified named
variables, how do each person and their group mates know what variables are what? How does the js, css and html work
together, they don’t seem to be imported and exported to one another? What would be the point of having numerous javascript
files for one page? How many lines of code does the average website have? What other languages are there for fullstack
developers instead of just HTML, CSS and Javascript?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours to work on this project, something I would like to implement an array of new features (pun intended :) ). As of now, the memory game allows for three tries per play and 6 buttons, I would like to create two dropdown or input boxes with descriptions to alter the amount of tries a player can receive and the number of colors a player has to tap so that the game can change in difficulty. Despite being able to alter the game’s properties, I would like the game to have another button for a basic mode of four colors, 0 tries and a near unlimited randomized patterns array so that I can add another detailed feature in the form of a leaderboard. The leaderboard’s function is pretty simple, to have the top 3 to 5 players’ score while having each color or sound they remember represent one point. In terms of aesthetic changes, the game’s background seems pretty bland and one dimensional, so possibly another button on top allowing the changes between dark mode and light mode would also be added to my current project. Another aesthetic feature that I would change would be the alert of winning and losing the game, adding some balloons pop up on the screen during a win or switching to a black and white screen to represent a loss may also be implemented.

## License

    Copyright [Junhui Zhang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
