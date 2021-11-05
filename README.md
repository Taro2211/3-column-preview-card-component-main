# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover states for interactive elements

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/3-column-preview-card-component-challenge-using-html-css-css-float-_hjQfTqjx](https://www.frontendmentor.io/solutions/3-column-preview-card-component-challenge-using-html-css-css-float-_hjQfTqjx)
- Live Site URL: [https://taro2211.github.io/3-column-preview-card-component-main/](https://taro2211.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Float
- Desktop-first workflow

### What I learned

How to make an element have a fixed position within its parent element using ```posititon``` property:
```css
section {
    position: relative;
    width: 33.33%;
    height: 575px;
    float: left;
    padding: 50px;
}
button {
    position: absolute;
    bottom: 50px;
    border: 2px solid hsl(0, 0%, 95%);
    border-radius: 30px;
    text-transform: capitalize;
    font-family: 'Lexend Deca';
    padding: 15px 40px;
    background-color: hsl(0, 0%, 95%);
}
```

### Useful resources

- [https://www.w3schools.com/](https://www.w3schools.com/)
- [https://stackoverflow.com/](https://stackoverflow.com/questions) 

## Author

- Frontend Mentor - [@Taro2211](https://www.frontendmentor.io/profile/Taro2211)
