# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nabil Fayak**

Time spent: **15** hours spent in total

Link to project: [https://elite-saber-stretch.glitch.me/](https://elite-saber-stretch.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Increase game timer with every correct guess
- [x] Animated Background
- [x] Start and Stop Buttons change color on hover
- [x] Creator name linked to personal website and github icon linked to GitHub
- [x] Clicking start button takes you to the game screen and removes start screen, clicking stop button does the opposite

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![Three Strikes and Personal Links Showcase](https://user-images.githubusercontent.com/72051470/162619067-48c068f4-5910-4584-9dc4-22a245ae6ef8.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[StackOverflow, W3Schools, Gradient-Animator]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge I encountered was incorporating the three strike system for the user/player. At first, I was unsure with how to start tracking invalid guesses made by the player. After reviewing the Prework videos and code, I was able to learn more about how the guess and progress variables work. I decided that using a variable to keep track of invalid guesses would be a great starting place. Once I had my variable initialized, I needed to outline exactly how would the invalid guesses counter go up, and eventually hit 3, where it would be game over. I looked through the code again, and found the conditionals at the end of the script and decided to just add an "if" "else" statement to it. I ended up having to modify one of the original statements to not end the game on one bad guess, and instead each bad guess would increment the counter. The additional if statement I added just checked to see when the bad guess counter hits 3 and once it does, then it's finally game over. This was just one of the more difficult challenges I faced while building my project, but I was able to overcome it by reviewing the code I already had and the Prework materials CodePath provided already.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[One question I have about web development, now that I created this project, is whether webpages such as this could be created without the use of HTML, CSS, and JS? To clarify, I'd like to ask if instead of using three different languages; one for information, one for styling, and one for functionality-- could you create something like this with just the use of one language? Having to switch back and forth between the three languages became confusing and somewhat arduous as functionality and aesthetics increased, the amount of readjusting across the different files also drastically grew. I would love for there to be maybe a different library, framework, or language that could act as a one-stop shop for use cases such as this.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a couple more hours to work on this project, I'd most likely spend them trying to improve the overall design with some smoother animations or fading the screens in and out as well as try to implement a highscore feature. It would be great if the player was greeted into the game with just the start button and once clicked then maybe the game buttons would fade into view, almost like an animation style event. Also once a player loses or wins, it would be great if there could be a label under the game with the highscore for the game as well as the player's name who acheived that high score. These are the two most realistic changes and improvements I believe I could make if there was a couple more hours left for me to complete this project. It was fun implementing the changes I was able to within the timeframe, but there's still plenty of ideas I have for how to take this game to the next level.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://baruch.zoom.us/rec/share/jaEzDnEgVwXD4Kl78rOaJKjfSq0pqDxixBRSG60sSSYgPUtpD43q22vd5K7BGp32.qhLSQzZ7gSVf0Qd4?startTime=1648880861000)


## License

    Copyright [Nabil Fayak]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
