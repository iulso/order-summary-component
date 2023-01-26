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
  - [Useful resources](#useful-resources)

## Overview

### The challenge

- Build a component with HTML and CSS with a given design and get it looking as close to it as possible.
- Users should be able to see hover states for interactive elements.

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Live Site URL: [click here](https://iulso.github.io/order-summary-component/)
- Solution URL in Frontend Mentor: [click here](https://www.frontendmentor.io/solutions/order-summary-component-OKQ5AUjVAv)

## My process

### Built with

- Semantic HTML5 markup
- CSS variables
- Flexbox
- [BEM methodology](https://en.bem.info/methodology/)

### What I learned

With the goal of not repeating CSS code, I tried to apply styles to broader classes as much as possible and only adding modifications when needed.

On one hover state I used the `filter` CSS property, supported by all modern browsers:

```css
.btn_primary:hover {
  filter: brightness(1.8);
  color: var(--very-pale-blue);
}
```

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a comprehensive guide to CSS flexbox layout.
