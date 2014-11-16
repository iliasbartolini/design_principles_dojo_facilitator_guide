Facilitator guide for "Software design principles: tensions &amp; synergies dojo"
================================================================================

Support slide deck
------------------
See `design_principles_presentation_deck.odp` in this repository


Preparation
-----------
Remind people to setup their environment with:

1. `java-jdk` >= 1.6
2. their favourite Java IDE or Editor (IntelliJ, Eclipse, ...)
3. optionally `gradle` 

Try to limit the partecipation to 20 people / 10 pairs: over this limit is difficult to manage

Instead of using the spreadsheet, try to prepare the matrix of principles with some cards/stickies and put it on the wall.

Enough Post-it and Sharpies


Agenda
------
1. Divide into pairs 
2. Start setup development environment
3. Explain the tensions & synergies
4. Choose a design principle or rule
5. Explain the Game of life
6. Implement a new user story (30min)
7. Showcase changes 
  * How did it affect other principles?
  * Repeat
8. Collect tensions and synergies with post-its 
  * https://docs.google.com/spreadsheets/d/1jiqS5soI0PCo8Rm4M6LFJ20L3I6yJeyuOjLAK23RDWY/edit?usp=sharing 
9. Conclusions
10. Feedback


Facilitation tips:
------------------
* Find co-facilitator expecially if the group is big
* Add ground rules in the beginning if you need to manage big groups
* To create pairs ask people to divide in "who has a laptop", "who knows java well" and try to mix them. You can ask people to stand up and create a queue based on their level of knowledge.
* Invite someone else to explain the Game Of Life. "Who knows the game of life?"
* If after 4-5 minutes people are stuck invite to do the smallest change to implement the story than refactoring. Avoid "Analysis paralysis"
* If people are shy to come on stage to share their code ask the last presenter to randomly pick up next pair
* ...


Ideas to try or changes to be made:
-----------------------------------
* Add other languages
* Try different starting point to see if it affects the outcomes
* Break coding session in shorter timeboxed parts
* Try variations of the zombie story
  * Random input
  * Click on the interface to change state
  * Implement a 3-d world (refactor the neighbours() back to the world)
* Leave and additional challenge at the end when people leave (eg. another possible story)
* Showcase some pre-prepared examples about how to apply some principles
* ...


After
-----
Ask people if they want to push their code to write in the README.md:

* which principle they tried
* their learnings

Share the speadsheet with the results:
https://docs.google.com/spreadsheets/d/1jiqS5soI0PCo8Rm4M6LFJ20L3I6yJeyuOjLAK23RDWY/edit?usp=sharing

If they want to repeat the dojo or do with other thay can refer to this guide


The example codebase:
---------------------
https://github.com/iliasbartolini/design_principles_dojo
