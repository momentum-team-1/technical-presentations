# Technical Presentation

## Phase 1

On Thursday of the last week of the phase, (*May 14, 2020*), each student will give a short technical presentation about a project that they worked on during the first phase.

The talk should be 5-6 minutes long. You'll be speaking to fellow students and the instructors. You do not need slides or a script. Just be yourself and tell us about the code you wrote.

The goals of this presentation are to give you experience talking about your code and to demonstrate that you can use the tools taught in Phase 1 to build a dynamic web page or application. It is also a chance to note how much you have learned, to celebrate how hard you’ve worked, and to show your readiness to move into the next phase of your coding education.

### Instructions

Choose a JavaScript project that you worked on that shows what you learned about HTML, CSS, and JavaScript.

* The project should be complete (that is, it meets the criteria of the original assignment) and without errors.

* The project must include JavaScript, so you can choose anything from week 2 on.

* The size of the project is not important. You should choose a project that you liked doing and that you are excited to talk about.

* You are not expected to sound like an expert or to remember all the right words for everything!

Your task:

* Explain what the project is. Show it from the user perspective first. What does it do? Tell us about it in plain language.

* Describe the technical details of your project.

  * What interesting problem(s) did you have to solve to build it?

  * How is it put together and how does it work?

  * Talk about what you did.

You don’t have to read the code to us, but you should be able to describe how the code works in terms that your technically skilled audience can understand.

### Example

Here’s an example of how you might talk about a project. This example project is a matching tile memory-style game for the browser.

*I built this memory game using HTML, CSS, and JavaScript. If you click on one of these tiles, it flips over to reveal the other side. Then you can click on another tile to see if you’ve found a match.*

*The tiles are just divs arranged using flexbox and styled with some simple CSS. I used JavaScript in conjunction with CSS to create the flip effect.  Here is the code that does that. On line 14, the event listener on the tile is triggered by a click. In the callback function, I’m adding a class, which applies a CSS animation to the tile that makes it spin and change appearance.*

*The other interesting thing I figured out for this project is how to compare the tiles to see if they match. The value of the tiles are stored in a data attribute, and they are just strings that correspond to the font icon on the tile. If the tiles match, then the pair is removed from the board. To keep the shape of the board, I don’t remove the elements from the DOM but just set a "hidden" attribute on the tiles that are no longer in play. There are some more animations there to make the effect seem smooth.*

*The game ends when all the matches have been found. I show the number of tries that it took to find all the matches, and the user sees an option to play again, which will reset the score and redraw the board. The trickiest part of that was...but here’s how I did it….*

### Evaluation

Your instructors will assess the work you’ve done and determine whether you will go on to the next phase.

The criteria for passing the phase are…

* Your project is complete (meets criteria in the original assignment).

* You can explain how your code works. Instructors may ask you about any portion of it and you can give a reasonable explanation.

You might be asked to repeat the phase if…

* You are unfamiliar with how your code works.

* You have nothing to present.
