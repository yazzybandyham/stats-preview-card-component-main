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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Solution](https://github.com/yazzybandyham/stats-preview-card-component-main/)
- Live Site URL: [Live site](https://yazstatspreviewcomponent.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned
In this challenge I built for mobile first and then used Media Queries to build for desktop. 

I also learned a new way of adding an overlay colour ontop of an image:

To see how you can add code snippets, see below:

```html
 <div class="image">
    <div class="image-overlay"></div>
  </div>
```

```css
.image {
    background: url(/images/image-header-mobile.jpg) no-repeat center/cover;
    border-radius: 0.5em 0.5em 0em 0em;
    overflow: hidden;
}

.image-overlay {
    background-color: hsla(277, 64%, 61%, 0.712);
    height: 300px;
    border-radius: 0.5em 0.5em 0em 0em;
    mix-blend-mode: multiply;
}
```

### Useful resources

- [Stats Preview Component by tsbsankara on YouTube ](https://www.youtube.com/watch?v=2tlbKm8_4mg&t=2553s) - This helped me understand how to use media queries correctly and create an color overlay over the backrgound image in CSS.

## Author
- Frontend Mentor - [@yazzybandyham](https://www.frontendmentor.io/profile/yazzybandyham)
- Twitter - [@yazzybandyham](https://www.twitter.com/yazzybandyham)

