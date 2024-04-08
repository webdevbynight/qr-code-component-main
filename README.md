# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot of the solution](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/webdevbynight/qr-code-component-main](https://github.com/webdevbynight/qr-code-component-main)
- Live Site URL: [https://webdevbynight.github.io/qr-code-component-main/](https://webdevbynight.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS (via SCSS)
  - custom properties
  - logical properties
  - flexbox
  - grid
- Mobile-first workflow

### What I learned

For the card shadow, I wanted to use `rgb()` following the relative colour syntax (e.g.: `rgb(from black r g b / 4.77%)`), but Firefox did not support such a syntax yet at the time I did this challenge (see [CSS relative colour syntax support on Can I Use](https://caniuse.com/css-relative-colors)). Instead, I used the basic `rgb()` syntax like this: `rgb(0 0 0 / 4.77%)`.

For the QR Code, I wanted to implement a SVG version of it (exported from the Figma file). I tested it and it works (tested with an iPhone 14 and a 9th-generation iPad).

## Author

- Website - [Victor Brito](https://victor-brito.dev)
- Frontend Mentor - [@webdevbynight](https://www.frontendmentor.io/profile/webdevbynight)
- Mastodon - [@webdevbynight](https://mastodon.social/@webdevbynight)
