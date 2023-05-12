# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover states for interactive elements

### Screenshot

![](./images/screenshot%20order%20summary%20component.png)

### Links

- Solution URL: [Github](https://github.com/Yakobus-Mardi/Order-summary-component)
- Live Site URL: [](https://yakobus-mardi.github.io/Order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I built this project with CSS flexbox - I learnt how to round the corners of the container, for the first time the border radius property didn't work, so I tried to set outline property to see why the border radius did not work. The border radius worked on the outline, but not the container. I tried to find the answer of the problem on Google and I found out the answer - use the overflow property and set the value to hidden.

```css
.container {
  border-radius: 20px;
  overflow: hidden;
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
