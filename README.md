# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [My Social Links](#My-Social-Links)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

<a href="screenshot/Desktop-Preview.png">Desktop Preview</a>
<br>
<a href="screenshot/Mobile-Preview.png">Mobile Preview</a>

### Links

- Solution URL: [FrontEnd Solution](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc/hub/single-price-grid-component-bO-wK7mZ-)
- Live Site URL: [Netlify](https://suspicious-joliot-c5e92e.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project I learned the uses of Grid to build a different layouts.

```html
<div class="container">
  <div class="whiteBGsection">...</div>
  <div class="left-cyan">...</div>
  <div class="right-lightcyan">...</div>
</div>
```
```css
.container {
  flex: 1;
  max-width: 64.3rem;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, auto);
  box-shadow: 0 0 10px #b8c2c6;
  margin: 2.5rem;
  border-radius: 0.8rem 0.8rem 0 0;
}
```

## My Social Links

- Frontend Mentor - [@Just9krish](https://www.frontendmentor.io/profile/Just9krish/)
- Instagram - [@Just9krish](https://www.Instagram.com/just9krish/)
- Twitter - [@Rvamit2648](https://www.twitter.com/rvamit2648/)