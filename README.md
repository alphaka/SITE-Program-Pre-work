# Pre-work - _Memory Game_

Hello from Alpha is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: ALPHA

Time spent: 2 hours spent in total

Link to project: https://glitch.com/edit/#!/blossom-climbing-icicle?path=README.md%3A13%3A13

## Required Functionality

The following functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![ezgif com-gif-maker](https://user-images.githubusercontent.com/63592880/112417755-9b4c9000-8cfe-11eb-8ab2-10fe79d364c8.gif)


## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- HackMD
- W3Schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?

The main challenge I encountered in creating this submission is about the "script.js" file, especially its functions. I have been learning JavaScript
for a while now and I usually forget it after a while without using it. Inside the .js file, the first thing that trigged my attention was the getElementById() function. It was difficult for me to understand what that function does. Hopefully, that is why we have documentation that guides programmers. The Document Object Model helped me understand this function operation; which is that getElementById() lookup for an HTML element with a specific id attribute that matches the argument passed through the function, for our case startBtn or stopBtn.

Lastly, the playSingleCue()'s setTimeout() function was my second dilemma. This was my first time using such a fascinating function. This function seems tricky due to its mode of operation. It takes as parameters one function that can be called in the future after a specific time given by its second parameter. Letting just that sink in my head took a while. The third parameter of the function allows us to reset "btn" to its original function in our case.

Fully apprehending the setTimeout() and getElemById() where my greatest dilemma for this project. I have a decent knowledge of CSS and HTML, as result, I did not encounter an issue writing those files.

3. What questions about web development do you have after completing your submission? 

The main question about web development that I would love to have an answer to is how do all the "index.html", "script.js", and "style.css" files work together to display a dynamic page. In other words, what specifically allows us to use all these three powerful, HTML, CSS, and JavaScript, languages to create a single product? I find this phenomenon quite interesting.

Secondly, I know that copyrights are extremely important nowadays as they give us a sense of control over our intellectual property. My question is, how do web developers feel in general about their codes being seen effortlessly by anyone throughout the world wide web? I mean, anyone can see the tedious work behind a developer webpage by looking up the "View Frame Source" and display their source code. What do they think about that?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific.


If I had more time, I would go into more detail over the different functions used for this project and get a solid grasp of their functionality and make some improvement. More importantly, I will have made the game more challenging by adding more buttons. 

One of the tremendous improvements to the program I would have made would be generating random numbers for the pattern array. I understand that the light and sound game is designed to make it as simple as possible because we are beginners. However, after ten games, with the current design, I believe most users will guess that the game follows the same pattern each time. Therefore, generating 8 new values for the pattern array will allow the user to have a different experience during each session. That would have been a huge update to the game.

## License

    Copyright Alpha Kaba

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
