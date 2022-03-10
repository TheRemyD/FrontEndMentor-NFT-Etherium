# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This project is another challenge from the FrontEnd Mentor site. The idea is to create an interactive card element with hover states.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![Etherium NFT Card](./images/NFT%20Etherium%20Screenshot.png)

### Links

- Solution URL: [Github Code](https://github.com/TheRemyD/FrontEndMentor-NFT-Etherium)
- Live Site URL: [Github Page for Etherium NFT Card](https://theremyd.github.io/FrontEndMentor-NFT-Etherium/)

### Built with
- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

Everything went smoothly for this project up until I was working on the image overlay. I was consistently getting a bit of space showing up under the image that I could not seem to get rid of. This led me to reaching out on Twitter and the online community did not fail. @intelagense figured out that by reducing font-size to zero on the parent element the space disappeared. A little digging on StackOverflow and I was pointed towards the fact that inline-block elements have space added to them.

By changing the image to
```css
display: block;
```

I was able to smoothly correct the issue.

## Author

- Website - [Remy Dale](https://www.remydale.com)
- Frontend Mentor - [@TheRemyD](https://www.frontendmentor.io/profile/TheRemyD)
- Twitter - [@TheOnlyRemyD](https://www.twitter.com/theonlyremyd)
- LinkedIn - [Remy Dale](https://www.linkedin.com/in/remydale/)

## Acknowledgments

Thank you to: @intelagense for aiding me on twitter