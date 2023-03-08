# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- View the optimal layout depending on their device's screen size. There are two layouts: mobile and desktop.

### Screenshots

![screenshot-mobile](images/screenshot-mobile.png)
![screenshot-desktop](images/screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/harnettd/stats-preview-card](https://github.com/harnettd/stats-preview-card)
- Live Site URL: [https://harnettd.github.io/stats-preview-card/](https://harnettd.github.io/stats-preview-card/)

## My process

### Built with

- HTML
- CSS
- Sass
- Flexbox
- Mobile-first workflow

### What I learned

In completing this challenge, I learned how to

- design flexible, responsive layouts using Flexbox, *e.g.,*
```css
$extra-large: 1200px;

  .card {
    display: flex;
    flex-direction: column;

    @media screen and (min-width: $extra-large) {
      flex-direction: row-reverse;
    }
```

- produce organized and easy-to-maintain stylesheets using the Sass preprocessor

- display responsive images using the `picture` HTML element, *e.g.*
```html
   <picture>
      <source srcset="images/image-header-desktop.jpg" media="(min-width: 1200px)">
      <img class="image-header" src="images/image-header-mobile.jpg" alt="image-header">
   </picture>
```

### Continued development

- To tint the header image, I positioned a `div` directly on top of it and adjusted the `background-color` of the `div` until the result looked like the design image from Frontend Mentor. I wonder if there's a simpler way. 

### Useful resources

- [W3Schools CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) - This is where I learned about flex containers, flex items, and flex responsiveness.
- [Sass](https://sass-lang.com/) - This is where I learned how to install and use Sass. (I love Sass!)
- [The Picture Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This is where I learned how to use the HTML `picture` element.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.
