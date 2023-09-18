# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/mysolution-product-preview-card-component.jpg)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/product-preview-card-component-challenge-solution-using-css-grid-CLOOvwea0F)
- Live Site URL: [Add live site URL here](https://leo-code-ca.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have experimented a bunch of new things while working on that project and I'm glad I did so! 

It's the first time I've tried to use the "mobile-first" approach and I think I definitely liked it. 

Outside of FreeCodeCamp's projects, it's also the first time I've used CSS grid instead of flexbox (it was hard for me to resist though, I LOVE flexbox). Actually it's pretty funny to use!

```css
.container-bottom {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 0.8fr 2fr 2.5fr 2fr 50px;
}
```

It was also my first time working with SVG, actually I haven't had much to do with it as I already had the code but at least I learned different ways to use SVG into my own code. I thing it's gonna be really useful for future projects. 

### Continued development

I love so much working with CSS animations. I definitely want to use them more in the future and to learn how to create some good ones that make a webpage more valuable. Of course, I'm also looking forward to learn how to create some with JavaScript but I'm still at the beginning of my journey with this language so, step by step!

I also want to use more CSS grid as I know it's a really powerful tool that can be used to design complex layouts. 

### Useful resources

- [CSS Grid Guide](https://www.freecodecamp.org/news/complete-guide-to-css-grid/#what-is-css-grid-s-justify-self-property) - This helped me SO MUCH to understand better how CSS Grid works. It's a really well done guide with a lot of informations. I highly recommend!
- [Animation delay](https://css-tricks.com/css-keyframe-animation-delay-iterations/) - This helped me to create a "delay effect" between each iteration of my animation as it's unfortunately not possible with the `animation-delay: 3s;` property as it only creates a delay before the first iteration. 

## Author

- Frontend Mentor - [@Leo-Code-CA](https://www.frontendmentor.io/profile/Leo-Code-CA)
- FreeCodeCamp - [@Leo-code](https://www.freecodecamp.org/Leo-code)
