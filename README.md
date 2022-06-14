# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot
#### `Desktop` Design Preview
![](/screenshhots/desktop-design.png)
![](/screenshhots/desktop-preview.png)
#### `Mobile` Design Preview
<p align="center">
<img height="667" width="375" src="/screenshhots/mobile-design.png"/>
  </p>

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://simple-website-with-html-and-css-position.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS position
- Mobile-first workflow

### What I learned

While creating this project I learned how to center any object in CSS with the help of CSS properties like position and transform. Similarly, I also learned to apply shadow to those object.

```css
.inner-rectangle{
    height:53vh;
    width:35vh;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
    background-color:hsl(0, 0%, 100%);
    border-radius:4%;
    box-shadow: 0px 12px 12px hsla(220, 15%, 55%,0.2)
}
```
