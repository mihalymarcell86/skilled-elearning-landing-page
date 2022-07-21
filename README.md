# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

Desktop

![](./screenshots/screenshot-desktop.png)

---

Tablet

![](./screenshots/screenshot-tablet.png)

---

Mobile

![](./screenshots/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/mihalymarcell86/skilled-elearning-landing-page](https://github.com/mihalymarcell86/skilled-elearning-landing-page)
- Live Site URL: [https://mihalymarcell86.github.io/skilled-elearning-landing-page/](https://mihalymarcell86.github.io/skilled-elearning-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- Sass, BEM
- Mobile-first workflow

### What I learned

Positioning the hero image was a bit troublesome, because the dimensions provided in the design didn't exactly match the image files. I used an image-wrapper `div` to define the dimensions of a relevant area and positioned everything according to that. Much like defining a `viewBox` in an SVG file. This was also a great opportunity to practice using the `<picture>` element for adding alternative image formats to the document, and for art direction.

### Continued development

I wanted to make my `.scss` / `.css` files more human-readable. I realize, that the `lerp()` function creates a lot of jumble in the code. However I found no way to get a Sass function generate a comment in the output. I will take a closer look at PostCSS, because I think, developing a plugin could be a good alternative.

## Author

- GitHub - [@mihalymarcell86](https://github.com/mihalymarcell86)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/mihalymarcell86)
