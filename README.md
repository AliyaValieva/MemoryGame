# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aliya Valieva**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/languid-outstanding-bergamot?path=README.md%3A78%3A34

## Required Functionality

The following **required** functionality is complete:

* [+] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [+] "Start" button toggles between "Start" and "Stop" when clicked. 
* [+] Game buttons each light up and play a sound when clicked. 
* [+] Computer plays back sequence of clues including sound and visual cue for each button
* [+] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [+] User wins the game after guessing a complete pattern
* [+] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [+] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [+] Buttons use a pitch (frequency) other than the ones in the tutorial
* [+] More than 4 functional game buttons
* [+] Playback speeds up on each turn
* [+] Computer picks a different pattern each time the game is played
* [+] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] Reaarnge the buttons in a random order after the player wins 3 times in a row

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/HkLhXFn.gif)
![](https://i.imgur.com/vMXHpB6.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- https://www.w3schools.com/css//css_text.asp
- https://www.w3schools.com/cssref/css_colors_legal.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One issue I had was my game not working and having a numch of errors in the console after I tried to start it. I was going through all of my code for solid 30 minutes with instructions line by line putting a bunch of print statements. Eventually, I realized missing playClueSequence() function in my startGame(). 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am curious as of how proficient in CSS/HTML should a web developer be to be considered a successful developer. Surely there are bondaries towards how succesful ypur product is. However, how would one determine whether his product is good enough? In the meantime, as specifically to this project would it be also possible to extend the folloiwng game even more and how much more shoudl it be? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would have definitely finished adding aditional features like pictures and sounds. Every time the button is clicked I would have a picture emerging along with a particular sound associated with it.
In the meantime, I would add a timer on the upper right corner to let the player see how much time has passed since they started. I wish I implemented a visual clue in a form of the number of won/lost tries. I also would reaarange the buttons in a random order after the player went through certain number of wins. 



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
