# Coding, Figures and Visuals

| Week | Date | In Class | Homework |
| ---  | ---  | ---      | ---      |
|  W1 | Wed 2018-10-03 | Introduction<BR>Course documents<BR>Clock designs<BR>First steps with Processing | Clock research |
|  W2 | Thu 2018-10-11 | More Processing: loops and lists<BR>Matrices: rotation and translation | Bauhaus lamp<BR>First steps with time |
|  W3 | Thu 2018-10-18 | Working with fonts and text<BR>Time functions<BR>Lists and mapping | |
|  W4 | - | Reading week | Visual clock design |
|  W5 | Thu 2018-11-01 | *Formative presentations*<BR>Clocks and interaction| |
|  W6 | Thu 2018-11-08 | Introduction to Arduino | |
|  W7 | Thu 2018-11-15 | Breadboarding<BR>Coding techniques in C | |
|  W8 | Thu 2018-11-22 | One-button techniques<BR>Serial interaction | |
|  W9 | Thu 2018-11-29 | Deeper C coding<BR>Design documentation | |
| W10 | Thu 2018-12-06 | *Formative presentations*<BR>Design finesse | |
| W11 | (Thu 2018-12-13 10:00) | *Summative hand-in* | |

## Homework

### Week 1

Visit the [Science Museum](https://www.sciencemuseum.org.uk/) (specifically the [Clockmakers' Museum](https://www.sciencemuseum.org.uk/see-and-do/clockmakers-museum)), and/or the [Greenwich Observatory](https://www.rmg.co.uk/royal-observatory), and look at some clocks.

- Which ones interest you, and why?
- Have you found anything unusual or surprising in design or construction?
- Do you understand how they all work, and how they are constructed?

### Week 2

A little bit of tidying up, and a bit of preparation for next week.

- Now that we've looked at for-loops, go back to the "Bauhaus lamp" image (see the Feed on Aula to find it). Can you draw the pull-chain part of that image? (Notice that the individual links are rounded in appearance - look at the documentation for `rect()` to work out how to do that.) As a bigger exercise, can you complete the rest of the image? (Don't worry about the text: that is a bit more complicated, and we'll look at drawing text in Week 3.)
- It's time to start looking at time. Processing has a number of functions for querying the time, such as `second()`, documented [here](https://py.processing.org/reference/second.html). Can you build an animation using the `second()` function? It returns a value between `0` and `59`, so how would you build something to indicate the seconds value? That might be reflected as an object's position in the window, or its size, or its colour. Whatever design you choose, it should reset itself every minute.

### Week 3

Reading Week! Not too much to do in terms of coding, but now it's time to do some design!

Coding exercises first:

- Can you finish off the digital clock that we started on this afternoon? It should look something like this:

![Digital Clock](clock.png)
