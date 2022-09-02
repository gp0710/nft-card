## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [click here](https://github.com/gp0710/nft-card)
- Live Site URL: [click here](https://gp0710.github.io/nft-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
Always use DevTools to help guide you for styling your code.

I had multiple containers where the dimensions were off, and working backwards in DevTools helped me resolve the issue with the dimensions.

My biggest challenge was overlapping the svg with the prism cube image. For that, I created two containers with the same width and height, and I added the svg using CSS instead.

```css
div.image > img:hover {
    opacity: 0.2;
}

div.papa-image:hover {
    border-radius: 15px;
    background-image: url('images/icon-view.svg');
    background-position: center;
    background-repeat: no-repeat;
    background-color: var(--cyan);
    opacity: 1;
    cursor: pointer;
    max-width: 100%;
    border: none;
    align-items: stretch;
}
```
Hope that helps anyone else with the same challenge!

### Continued development
I would like to get more comfortable with grid-layout, positioning, and SASS.

### Useful resources

- [Centering a Div](https://www.freecodecamp.org/news/how-to-center-a-div-with-css-10-different-ways/) - Helped me center the card on the page.

- [Background Position](https://www.w3schools.com/cssref/pr_background-position.asp) - How I centered the svg element.

