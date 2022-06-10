# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Self assigned challenges](#self-assigned-challenges)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Self assigned challenges

- Use BEM to organise CSS.
- Design mobile first, then move up to desktop size from there.

### Screenshot

![](./screenshot.png)

### Links

- [Solution URL](https://your-solution-url.com)
- [Live Site URL](https://samhemingway.dev/projects/stats-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- That you can use the `picture` html tag to change image source based on media queries. Before discovering this, I spent far too long trying to make this work via a background image or by hacking a new image overlay on top via `img::after` until I discovered that this simply doesn't work...

- Having not had much experience with grid so far, I tried using it to layout the stats area. I quickly realised that this was completely unnecessary and that flexbox was much better suited for this usecase.

### Continued development

- I wasted a lot of time and energy based upon an incorrect assumption that I couldn't change an image src in the DOM based on screensizes. If I'd simply Googled `Responsive images` I would literally have 2 more hours of my life back as I wouldn't have spent so much time trying out hacky shit.

### Useful resources

- [Creating responsive images](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/#aa-using-picture) - The glory of the `picture` tag which solved all my woes.

## Author

- Website - [Sam Hemingway](https://samhemingway.dev)
- Frontend Mentor - [@SamHemingway](https://www.frontendmentor.io/profile/samhemingway)

### Acknowledgements

- Big thank you to Grace on the FEM Slack channel who corrected my assumption that changing an image src at different screen sizes would need to be a js based solution and pointed me in the direction of the `picture` tag.
