# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screenshot%20from%202024-09-04%2004-31-04.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I Had no idea but now I do. I now know how to apply a color overlay to an image using the position, z-index, background and opacity properties, as well as displaying different pictures for different screen sizes using display property set to none if the image is not supposed to be displayed and inline or block if it has to be displayed, like in this case two copies of the same image with different sizes depending on the screen size, one for mobile and the other for desktop are provided. 

These are not the only ways but they are the methods which I managed picking up for this time. 


```css
#cover {
    position: absolute;;
    z-index: 1;
    opacity: 69%;
}
```
```css
#mobile-img {
    position: relative;   
}

#desktop-img {
    display: none;
}
```
```css
.proud-of-this-css {
  text-align: center;
}
```

## Author

- Frontend Mentor - [@alphastand27](https://www.frontendmentor.io/profile/alphastand27)
- Twitter - [@micheallifexp](https://x.com/micheallifexp)
