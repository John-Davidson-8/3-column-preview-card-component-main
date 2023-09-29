# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

The challenge is a to create responsive component card that has three sections detailing three different vehicles. In mobile view they are to be stacked one on top of the other. In desktop view they are to be side by side.

### The challenge

The challenge involves using html, css, css Flexbox and one media query. Also, the desktop version is to have the call to action tab change color when hovering over it.

### Screenshot

![](./readme-images/mobile-screenshot.pngng)

![](./readme-images/desktop%20screenshot.png)

### Links

- Solution URL: (https://github.com/John-Davidson-8/3-column-preview-card-component-main)
- Live Site URL: [](https://fem-3-column-preview-card-main.netlify.app/)

## My process

I began with mobile first and added a media query at 62 rem to change from flex column to flex row. I began with the html structure and moved on to css after using css classes as much as possible. I also created variables for colors and fonts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

What is interesting is I styled anchor tags without classes and it messed up the anchor tags in the footer. Must always use classes, saves a lot of hassle in the long run. Also, creating variables keeps things neat in css, in particular for colors and fonts. Below is a snippet of the anchor tag with a class attached.

```html
<a class="cta" href="#">Learn More</a>
```

Below is an example of setting up variables for primary colors.

```css
/* primary colors */
--clr-primary-1-orange: hsl(31, 77%, 52%);
--clr-primary-2-dark-cyan: hsl(184, 100%, 22%);
--clr-primary-3-very-dark-cyan: hsl(179, 100%, 13%);
```

### Continued development

Continued development includes learning CSS Flexbox and media queries. I must get to know these two practices well. Also, learning to use class names that are appropriate for what the component is achieving in the codebase.

### Useful resources

- (https://flexbox.malven.co/) - This helped me in my Flexbox understanding reason.

## Author

## Acknowledgments

Thanks to Alex in Frontend Mentor's Discord community for answering queries.
