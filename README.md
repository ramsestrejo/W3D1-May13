# The CSS Box Model

## Topics 
1. HTML5 semantic
2. Block Level Elements / Inline Level Elements
3. Styling with CSS
4. CSS Box Model
5. CSS Debugging in DevTools
6. Demo of Application 



## 1. Writing Semantic HTML5
Provides meaning and intent to web pages. Assist in communication with browsers, search engines and fellow developers. Examples are (nav, section, article, main, header). They give proper meaning to different sections in HTML documents and no longer depend on multiple and generic divs that add confusion and lead to time consuming troubleshooting.

## 2. Block vs inline Elements
Block elements 'block' the whole row of where they are in the browser , pushing any neighbouring elements down.
Inline elements take only the space that used by their contents, enough to hold itself.
Inline and block element act like block elements but they do not take entire width of the container, allows to set dimensions.
The display property is used to set the block behavior : block, inline, inline-block respectively.

## 3. Styling with CSS
Some useful facts about CSS:

* CSS stands for Cascading Style Sheet and it is used to control appearance of markup languages like HTML.
* CSS is a must learn for building front ends of web applications.
* Analogy : construct buildings with HTML & decorate them with CSS.


### CSS Rules
CSS is about writing styling rules by defining a selector and a declaration block.
The selector indicates element(s) subject to styling and the declaration block provides instructions for browser for formatting element(s).

Declaration blocks have property and value. It is recommended to use indentation, spacing and one line per declaration to increase readability.
The ways of specifying CSS styling are:
1. Use inline code directly in an HTML element (higher priority)
2. Use style block inside a web page
3. Use an external style sheet with a .css extension

Styles can be combined (even from different sources)

## 4. CSS Box Model
All HTML elements are considered boxes, many of these play the role of containers of other elements, and the way the width and height is calculated in the document becomes even more important. The box model setting determines how browser renders elements on the screen.

### Why is CSS Box Model important?
In order to set width and height of an element correctly in all browsers, and set expectations for sizing elements in the document. By default, the width and height of the content area is set via CSS and the total width and height for its "box" is determined by adding padding and border widths.

Actual visible/rendered width of an element's box = content width + padding + border 

Actual visible/rendered height of an element's box = content height + padding + border 

[Some history about the box model](https://css-tricks.com/box-sizing)
In conclusion, the box model is defined by the box-sizing property:
content-box is the default behaviour (element box dimensions are calculated by adding padding and border value)
border-box is equivalent to IE's “quirks mode" (element's padding & border are included in the box's width & height)

[Demo of the box model](http://guyroutledge.github.io/box-model)

## 5. CSS Debugging in DevTools
Google Chrome provides a great Development tool for fine tuning CSS (and HTML) on the fly, and helps speed up the development process and issue troubleshooting.


## 6. Demo of Application 
(https://web.compass.lighthouselabs.ca/projects/w3-tweeter?day_number=w03d1)






  