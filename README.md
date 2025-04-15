# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![(./mobile-solution.png)](https://github.com/KiwiCandy-ai/bento-grid/blob/main/desktop-solution.png?raw=true)
![(/desktop-solution.png)](https://github.com/KiwiCandy-ai/bento-grid/blob/main/mobile-solution.png?raw=true)


### Links

- Solution URL: [Click Here](https://github.com/KiwiCandy-ai/bento-grid)
- Live Site URL: [Click Here](https://kiwicandy-ai.github.io/bento-grid/)

## My process

This Bento Grid was a fun and creative challenge. I used Flexbox to build the entire project. 

I started with one container that filled the majority of the viewport. I then divided that container into two different elements, using <code>flex</code> to make the right hand container take up the majority of the parent element. 

Using a combination of <code>flex-direction:row</code> and <code>flex-direction:column</code> I created the inner containers for each card. 

Once I had the layout correct I could then design the individual elements which was a fun process. 

The tricky part came when adjusting for smaller screen sizes. In hindsight I should have built this mobile-first. But it was still do-able using <code>column</code> and <code>column-reverse</code> to adjust the order once the elements were stacked. 

The tools I used to complete this project were: 

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- @mediarules

### What I learned

- Using @media rules to adjust for mobile screen sizes

### Continued development

- I would also like to attempt this layout using CSS Grid.

- Mobile first solutions

## Author

- GitHub - [KiwiCandy-ai](https://github.com/KiwiCandy-ai)
- Frontend Mentor - [@KiwiCandy-ai](https://www.frontendmentor.io/profile/KiwiCandy-ai)

