# Coding, Figures and Visuals

| Week | Session | Date | In Class | Homework |
| ---  | ---     | ---  | ---      | ---      |
|  W1 | 1 | Wed 2018-10-03 | Introduction<BR>Course documents<BR>Clock designs<BR>First steps with Processing | Clock research |
|  W2 | 2 | Thu 2018-10-11 | More Processing: loops and lists<BR>Matrices: rotation and translation | Bauhaus lamp<BR>First steps with time |
|  W3 | 3 | Thu 2018-10-18 | Working with fonts and text<BR>Time functions<BR>Lists and mapping | Coding wrap-up exercises |
|  W4 |   | Reading week | Visual clock design and interaction |
|  W5 | 4 | Thu 2018-11-01 | *Formative presentations*<BR>Clocks and interaction | Post-formative breather! |
|  W6 | 5 | Thu 2018-11-08 | Introduction to Arduino | Ohm's Law<BR>Arduino basics<BR>C programming basics |
|  W7 | 6 | Thu 2018-11-15 | More breadboarding<BR>Serial interaction | Keyboard input, timer example |
|  W8 | 7 | Thu 2018-11-22 | Timers and one-button techniques | |
|  W9 | 8 | Thu 2018-11-29 | Deeper coding and revision<BR>Design documentation | |
| W10 | 9 | Thu 2018-12-06 | *Formative presentations*<BR>Design finesse | |
| W11 |   | (Thu 2018-12-13 10:00) | *Summative hand-in* | |

## Homework

### Week 1 / Session 1

Visit the [Science Museum](https://www.sciencemuseum.org.uk/) (specifically the [Clockmakers' Museum](https://www.sciencemuseum.org.uk/see-and-do/clockmakers-museum)), and/or the [Greenwich Observatory](https://www.rmg.co.uk/royal-observatory), and look at some clocks.

- Which ones interest you, and why?
- Have you found anything unusual or surprising in design or construction?
- Do you understand how they all work, and how they are constructed?

### Week 2 / Session 2

A little bit of tidying up, and a bit of preparation for next week.

- Now that we've looked at for-loops, go back to the "Bauhaus lamp" image (see the Feed on Aula to find it). Can you draw the pull-chain part of that image? (Notice that the individual links are rounded in appearance - look at the documentation for `rect()` to work out how to do that.) As a bigger exercise, can you complete the rest of the image? (Don't worry about the text: that is a bit more complicated, and we'll look at drawing text in Week 3.)
- It's time to start looking at time. Processing has a number of functions for querying the time, such as `second()`, documented [here](https://py.processing.org/reference/second.html). Can you build an animation using the `second()` function? It returns a value between `0` and `59`, so how would you build something to indicate the seconds value? That might be reflected as an object's position in the window, or its size, or its colour. Whatever design you choose, it should reset itself every minute.

### Week 3 / Session 3

Reading Week! A bit of coding, and a bit of design:

Coding exercises first:

- Can you finish off the digital clock that we started on this afternoon? It should look something like this:

![Digital Clock](https://raw.githubusercontent.com/codezoners/USE18103/master/images/clock.png)

- Note the background "shadow" to all the digits: can you reproduce this?
  
- Can you make the colons between the digits flash once a second? (In other words: "on" one second, "off" the next. Doing the "on"/"off" cycle within one second requires sub-second timing, and we've not looked at how to do that yet.)

- We worked with Python lists and iteration last session: if you're not sure how these work, do a bit of revision. There's a page on lists [here](https://www.w3schools.com/python/python_lists.asp).

- Integration: can you create a sketch which combines the digital clock with one of the other time-based animations we worked on last session? Think of it as a digital clock with animated decoration.

- Design: for your formative presentations, put together some provisional designs for your clock. These don't have to be coded: you can do hand sketches or use some other tools. Do at least two different designs. For each design, come up with an *interaction model* for the clock: how many modes does it have? What will the button(s) do (how many do you need?), and how will the interaction show itself on screen?

### Week 4

Reading Week continued.

### Week 5 / Session 4

Clock presentations.

### Week 6 / Session 5

We covered Arduino basics (LEDs, buttons, C coding) pretty quickly in class, so homework this time is about revision: basic electrical circuits, and the C coding we did to work with LEDs and buttons. You'll be expected to know this to continue with more Arduino work next week.

Some revision material for you:

- [Ohm's Law](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law/all) (voltage, current, resistance)
- [Arduino: Blinking LED](https://www.instructables.com/id/Arduino-Blinking-LED/)
- [Arduino: Button](https://www.arduino.cc/en/Tutorial/Button)

You'll need to buy some Arduino kit for your clock project next term, so you might as well do that now. You should buy:

- One [Arduino](https://uk.rs-online.com/web/p/processor-microcontroller-development-kits/7154081/)
- A [USB Cable](https://www.amazon.co.uk/dp/B00P0FO1P0/)
- One [breadboard](https://uk.rs-online.com/web/p/breadboards/1029147/)
- A [jumper wire kit](https://uk.rs-online.com/web/p/products/7916463/) (in fact, maybe get a couple of those - make sure they are male-to-male)

There will be additional stuff to buy next term.

We have LEDs, buttons and resistors that you can borrow, but if you want to get anything fancy (like the [expensive white LEDs](https://uk.rs-online.com/web/c/displays-optoelectronics/leds-led-accessories/visible-leds/)) then feel free to splash out. Watch the prices though - many have to be bought in quantities of 100.

For the C programming language, here's a [nice online resource](https://www.learn-c.org/). See how far you can get through the "Basics" section. I'll be assuming you've worked through these examples next week!

### Week 7 / Session 6

Well done on getting through the session yesterday! You now have experience in two very different programming languages, and we haven't even finished the first term yet.

There isn't much else to cover in terms of new material for this unit - you now know enough to finish the project to a good level of `quality. What we'll be doing over the remaining weeks is refinement: more practice in areas we've looked at already, filling in holes in understanding, and generally bedding down the skills you've acquired to date.

Here's a handful of exercises.

- If you don't have your Arduino kit yet, you won't be able to work on the Processing sketches we wrote, because they are triggered by the Arduino. Can you convert the timer sketch to work with computer keyboard input rather than Arduino input? (Make a copy of the sketch, since once you have an Arduino you'll go back to using that.) Look at the `keyPressed()` function [here](https://py.processing.org/reference/keyPressed.html) and the `key` variable [here](https://py.processing.org/reference/key.html).
- Can you make the timer "hands" start at the top of the window, not at the right hand side? (Think about how we calculate the rotation angle, and research into degrees vs. radians; for any 3D graphics work understanding radians is essential.)
- Harder: use the two buttons (or two keyboard keys) to implement a more sophisticated stopwatch. The first button should start and pause (press to start, press to pause, press to resume). The second button is a reset to zero. (If you get that working, do some research into lap timers and see if you can implement one of those!)
