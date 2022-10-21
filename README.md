# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

Desktop version :
![Desktop](https://github.com/iMegz/FrontendMentorChallenge_01/blob/master/screenshots/desktop.png?raw=true)

Mobile version :
![Mobile](https://github.com/iMegz/FrontendMentorChallenge_01/blob/master/screenshots/mobile.png?raw=true)

### Links

-   Solution URL: [solution URL](https://www.frontendmentor.io/solutions/responsive-product-card-challenge-ty0u2mQe-N)
-   Live Site URL: [live site URL](https://imegz.github.io/FrontendMentorChallenge_01/)

## My process

### Built with

-   HTML 5
-   CSS 3
-   Flexbox

### What I learned

Loading different images depending on screen size using <picture> tag

```html
<picture>
    <source media="(max-width:376px)" srcset="img/image-product-mobile.jpg" />
    <source media="(min-width:376px)" srcset="img/image-product-desktop.jpg" />
    <img
        src="img/image-product-desktop.jpg"
        alt="Gabrielle Essence Eau De Parfum"
    />
</picture>
```

### Useful resources

-   [w3schools](https://www.w3schools.com/tags/att_source_srcset.asp#:~:text=The%20srcset%20attribute%20specifies%20the,is%20used%20in%20.) - This helped me to understand how to use <picture> tag

## Author

-   Linkedin - [Ahmed Magdi](http://linkedin.com/in/imegz)
-   Frontend Mentor - [@imegz](https://www.frontendmentor.io/profile/imegz)
