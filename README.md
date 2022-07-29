# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Creating an order summary card with some responsive features (buttons changing color/cursor changing depending on its location)


### The challenge

Users should be able to:

- See hover states for interactive elements
- buttons change apperance when the cursor is on them
- cursor changes appearance when ontop of a button

### Links

- Live Site URL: [Add live site URL here](file:///Users/SamiaShamir/Documents/GitHub/Order-Summary-Challenge-/index.html

## My process
Built the basic structure with CSS Flex.
Struggled with the container that included the music note icon, the price and the change button. Used a youtube tutorial to help with this, the link can be found in the acknowledgements section.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Creating variables have made styling with the right colors much easier:

:root {
  --pale-blue: hsl(225, 100%, 94%);
  --bright-blue: hsl(245, 75%, 52%);
  --very-pale-blue: hsl(225, 100%, 98%);
  --desaturated-blue: hsl(224, 23%, 55%);
  --dark-blue: hsl(223, 47%, 23%);

This is the first time i've used the inherit property to copy a style from the parent element
  button {
    font-family: inherit;

Targetting mutiple classes through this naming convention, also able to target specific classes
.btn-change {

have included some comments in the styles.css sheet to highlight where new code has been used.


### Continued development

In order to complete this I followed a youtube tutorial from tsbsankara. This really helped me and also helped me learn some new techniques: https://www.youtube.com/watch?v=uaM5F8O_VI8
