# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot/sunnyside-desktop.png)
![](./screenshot/sunnyside-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/hkmarcoot/fementor-sunnyside-agency-landing-page)
- Live Site URL: [Add live site URL here](https://hkmarcoot.github.io/fementor-sunnyside-agency-landing-page)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

- Use SCSS for the first time.

- Use flex order in the image arrangement in desktop version.

```css
.flex-order-1 {
  order: 1;
}

.flex-order-2 {
  order: 2;
}

.flex-order-3 {
  order: 3;
}
```

- Use toggle in the JavaScript.

```js
const hamburger = document.querySelector(".hamburger");
const mobileMenu = document.querySelector(".menu-layout");

hamburger.addEventListener("click", function () {
  hamburger.classList.toggle("hide");
  mobileMenu.classList.toggle("menu-mobile");
});
```

### Continued development

The transition from mobile version to desktop version is not smooth. i.e. the description in middle section is not aligning in the middle before the page reaching 1440px width. In my opinion, it can be put in a container and instructed to always stay in the middle.

### Useful resources

- [MRZ.Code.Manufacture Tutorial](https://www.youtube.com/watch?v=U7ZZnILFO3w) - This tutorial is well constructed and easy to learn.

## Author

- Website - [Marco Tsang](https://www.linkedin.com/in/marco-tsang112)
- Frontend Mentor - [@hkmarcoot](https://www.frontendmentor.io/profile/hkmarcoot)
- Twitter - [@marcotsang112](https://www.twitter.com/marcotsang112)

## Acknowledgments

I need to say thank you to MRZ.Code.Manufacture as its tutorials teach me how to do this Sunnyside Agency Landing Page challenge. This is my first time using SCSS and I am so glad that the tutorials are easy to follow.
