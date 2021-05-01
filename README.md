# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![https://i.ibb.co/y8YhCnr/image-2021-05-02-001321.png]


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

What I've learned from this project is how to systematically break down components of a website and building each one from scratch. Being able to identify which components of the website will be the same/similar to each other and then setting up the HTML code before getting into the CSS styling.

After setting up the HTML, working on the CSS styling was tricky but overall a valuable experience in reminding me of the CSS box model & position elements (absolute/relative);

The only problem I encountered was including the buttons for all of the panels in the project. If you highlight the buttons, because they are anchor tag (buttons) placed inside an existing div-container, the highlight is equal to the amount of distance that is has been moved in regards to position:relative; - I came up with a fix where I would just include the buttons standalone outside of the div-containers and give them an absolute positioning. The only problem is that if I was to try and make the website responsive, then absolute positioning wouldn't work out well. But, it shouldn't be a problem since other content is usually included and would just push down the button's location on the website naturally.
