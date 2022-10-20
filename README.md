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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- desktop Preview

![](./design/desktop-preview.jpg)

- Desktop Design

![](./design/desktop-design.jpg)


- Mobile Design

![](./design/mobile-design.jpg)



### Links

- Solution URL: [Check My Solution Here](https://github.com/rereloluwavictor2001/Frontend-Mentor-Stats-preview-card-component)
- Live Site URL: [Check the Live Website Here](https://rereloluwavictor2001.github.io/Frontend-Mentor-Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

I learnt how to swap between two pictures for a responsive website with html tags. I also learnt how to order divs with css.

See code snippet below:

```html
  <picture>
    <source class="image1" srcset="images/image-header-mobile.jpg" media="(max-width: 975px)">
    <source srcset="images/image-header-desktop.jpg" media="(min-width: 975px)">
    <img class="image1" src="images/image-header-desktop.jpg" alt="image-header-desktop.jpg">
  </picture>
```
```css
.image1 {
    filter: opacity(0.4) drop-shadow(0 0 0 hsl(290, 80%, 45%)); 
}
.first-container {
    border-radius: 0 0 0.5rem 0.5rem;
    order: 2;
}
```

### Continued development

I'd still want to dive into filtering and colour blending and more of trying to learn how to order divs in a container.


### Useful resources

- Used MDN resources and w3schools


## Author

- Frontend Mentor - [@rereloluwavictor2001](https://www.frontendmentor.io/profile/rereloluwavictor2001)
- Twitter - [@rereloluwaalimi](https://www.twitter.com/rereloluwaalimi)


