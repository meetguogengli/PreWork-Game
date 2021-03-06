# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Guogeng Li**

Time spent: **10** hours spent in total

Link to project: (https://glitch.com/edit/#!/fantastic-glen-newsprint?path=style.css%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* &#x2705; Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* &#x2705; "Start" button toggles between "Start" and "Stop" when clicked. <br>
* &#x2705; Game buttons each light up and play a sound when clicked. 
* &#x2705; Computer plays back sequence of clues including sound and visual cue for each button
* &#x2705; Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* &#x2705; User wins the game after guessing a complete pattern
* &#x2705; User loses the game after an incorrect guess

The following **optional** features are implemented:

* &#x2705; Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* &#x2705; Buttons use a pitch (frequency) other than the ones in the tutorial
* &#x2705; More than 4 functional game buttons
* &#x2705; Playback speeds up on each turn
* &#x2705; Computer picks a different pattern each time the game is played
* &#x2705; Player only loses after 3 mistakes (instead of on the first mistake)
* &#x2705; Game button appearance change goes beyond color (e.g. add an image)
* &#x2705; Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:<br>
<br>
Player wins the Game!<br>
<img src = "http://g.recordit.co/m1MZTmHZhh.gif" width = 400><br>
Player loses the Game 3 times in a row!<br>
<img src = "http://g.recordit.co/8UNTWEm8xp.gif" width = 400><br>


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. <br>
https://www.w3schools.com/tags/tag_img.asp <br>
https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random <br>
https://programminghead.com/how-to-play-audio-in-html-using-javascript/
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) <br>
My first few features in this project went really well until the 5th optional
feature ???Spruce up your buttons???. Since I had no previous HTML development
experience, I had no idea where to start at first. But I was not discouraged
and tried my best to learn from recommended readings and google the issues I confronted with. 
After I read the recommended post, I began to have a clue and attempted to
insert an image into a button first, if successful, then other buttons can just
repeat the same thing. What makes me very happy is that the first button
successfully inserted the picture quickly, but it did not hide at the
beginning, then I started a long time to google search how to insert a background
image for the button and also set the image to hidden mode before the button was clicked.
Then I googled how to response the button to background image after being clicked.
Some part of the issues were hard to debug, so I I also tried to learn demo on YouTube. 
Then I start to make some draft to hide the inserted image of the button, after
trying many times, it finally succeeded! When I thought that this feature could
be solved by copying the same thing to other buttons, unfortunately, some bugs
showed up. When I inserted different background images for other buttons, There
are some bugs in the previous button which are when I click the previous
button, the inserted picture of the last button is always displayed. After
carefully debugging, I found that there is a function call that is
asynchronized on each button. Then I quickly fix the bug and thoroughly test
this feature.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) <br>
In this web development, I felt the fast-paced of front-end development with the outcomes
that are user-driven and Offer real-time programming. But I???m pretty curious
about how to optimize loading webpage faster? Does the webpage also convert the
front-end high-level code like HTML and Javascript to assembly code and then
convert the assembly code to binary code? Since I think running the binary code
will greatly improve the loading speed. And I???m also curious about how do large
Web sites handle a load of millions of visitors simultaneously, especially
during some online shopping festivals, such as Black Friday? How do they handle
that with the reduced cost? And what to do if the website crashes or becomes
inaccessible when they experience large traffic?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) <br>
If I had more time, I would consider more features. Such as the interactivity of the
gaming experience. From my gaming experience, the gaming experience I enjoy the
most is with my best friends, not myself stay at home and play games. So if we
can build the interactivity of this Light & Sound Memory game, for example, we
can allow two users to participate in the game together, let the first user
issue instructions in front. And then let the second user to follow. This would
be just like a teacher taught you to play the piano when you were a child and
you imitated the teacher's motions. In addition, we can also add some creative
features. For example, we can use these buttons with different sounds to create
some songs and then share our creations with friends.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/61d423cd2ac54c21b6dd5a634d7cbcd6)


## License

    Copyright [Guogeng Li]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
