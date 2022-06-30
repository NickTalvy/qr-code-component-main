# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](/images/Desktop1440.png)
![](/images/Mobile375.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/qr-code-component-html-and-css-only-yvRwEl2XVQ)
- Live Site URL: [Live Site](https://nicktalvy.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The biggest take away was learning @media. I added @media for tablet, in addition to the required desktop view. I think I did it correctly, but possibly used more code then necessary. 

```css
/* Tablet */
@media screen and (min-width: 600px) and (max-width: 999px) {
    .card {
        max-width: 45vw;
    }

    h2 {
        padding-inline: 0.09rem;
    }

    p {
        padding-inline: 0.4rem;
    }
}

/* Desktop */
@media screen and (min-width: 1000px) and (max-width: 1900px) {
    .card {
        max-width: 20vw;
    }
    
    h2 {
        padding-inline: 0.09rem;
    }

    p {
        padding-inline: 0.8em;
    }

```
### Continued development
I definitely need to continue to learn and understand how to align containers and content. I spent the most time making small adjustments by guessing.

### Useful resources

- [resource 1](https://www.w3schools.com/css/default.asp) - w3schools was a big help in figuring out how to align and size my container. Also, helped me understand @media and create my breakpoints.

## Author

- Website - [Nick Talvy](https://github.com/NickTalvy)
- Frontend Mentor - [@NickTalvy](https://www.frontendmentor.io/profile/nicktalvy)

## Acknowledgments

Thank you w3schools!
