# Codecademy - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.JPG)

### Links

- [Solution Link](https://github.com/heraldofortuna/stats-preview-card-component-main)
- [Live Site Link](https://heraldofortuna.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<div class="card__image">
  <div class="card__image--color"></div>
</div>
```

```css
.card__image {
  position: relative;
  width: 100%;
  height: 320px;
  background-image: url("./images/image-header-mobile.jpg");
  background-position: center;
  background-size: cover;
  border-radius: 8px 8px 0 0;
}

@media (min-width: 800px) {
  .card {
    width: 85%;
    display: flex;
    flex-direction: row-reverse;
  }
}
```

### Continued development

I definitely need to work and study more on image containers. I'm having trouble accommodating them in different sizes.

## Author

- Frontend Mentor - [heraldofortuna](https://www.frontendmentor.io/profile/heraldofortuna)
- Twitter - [@heraldofortuna](https://twitter.com/heraldofortuna)
