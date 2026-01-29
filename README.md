# Frontend Mentor - NFT preview card component

This is my solution to the NFT preview card component challenge on Frontend Mentor
. This project helped me practice responsive layouts, hover effects, and writing cleaner SCSS using variables and nesting.

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
### The challenge
 Users should be able to:
 
 - View the optimal layout depending on their device’s screen size
 
 - See hover states for interactive elements (image, title, creator name)



### Screenshot

![Hover state](./images/hover-state.png)
![small-device](./images/smaller-screen.png)
![Larger-device](./images/larger-screen-size.png)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-nft-card-preview-page-with-scss-flex-b0sMEJWq0L

- Live Site URL : https://nft-preview-card-beryl-theta.vercel.app/


## My process

### Built with
 - Semantic HTML5

 - SCSS (variables, nesting)

 - Flexbox

 - Mobile-first workflow

 ### What I learned

 This project helped me understand how to:

Use SCSS variables for colors so my design stays consistent

Create hover overlay effects using background images and opacity

Align content using Flexbox

Build responsive layouts with media queries

Example SCSS I’m proud of:
```scss
.img-container:hover {
  background: url(./images/icon-view.svg);
  background-color: hsla(178, 100%, 50%, 1);
  background-size: 10%;
  background-repeat: no-repeat;
  background-position: center;
  cursor: pointer;
}
```

This hover effect gave the NFT image a clean interactive feel.

### Continued development

In future projects, I want to:

 - Improve my responsive layouts

    - Write more reusable SCSS

    - Practice CSS Grid alongside Flexbox

    - Get better at organizing components

## Author

- Name: Awosanya Ifeoluwa Victor (Viipzy)

- Github - [Viipzy](https://github.com/viipzy)

- Linkedin - [@awosanyaVictor](https://www.linkedin.com/in/awosanya-ifeoluwavictor/)
