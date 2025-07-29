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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/127.0.0.1_5501_%20(14).png)

### Links

- Solution URL: https://github.com/DanKRT-Star/nft-preview-card-component-main
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM naming convention
- Mobile-first workflow

### What I learned

- How to structure a card component using semantic HTML.
- How to align inline image and text using display: flex; align-items: center;.
- How to create hover effects for interactive elements like images and text using :hover and transition.
- How to use position: absolute and transform: translate(-50%, -50%) to center the view icon in the middle of the image.
- How to apply border-radius and box-shadow to create a clean, modern UI look.

```css
.images_container .see_more {
    position: absolute;
    top: 50%;
    left: 50%;
    translate: -50% -50%;
    visibility: hidden;
    opacity: 0;
}
```

### Continued development

In future projects, I want to:
- Improve accessibility (e.g., using ARIA labels and better alt texts).
- Learn more about responsive typography techniques.
- Use CSS Grid for more complex layouts.
- Convert the project into a reusable component using React.

### Useful resources

- [Kevin Powell - CSS layout tips](https://www.youtube.com/kevinpowell) - Great tutorials for flexbox, responsive design, and CSS architecture.
- [CSS Trick Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped me better understand alignment options.
- [MDN Web Doc](https://developer.mozilla.org/en-US/) - My go-to resource for checking syntax and CSS behavior.

## Author

- Frontend Mentor - [@DanKRT-Star](https://www.frontendmentor.io/profile/DanKRT-Star)
- Facebook - [Lê Mạnh Đan](https://www.facebook.com/le.manh.an.887330)
- Gmail - [Lê Mạnh Đan](tonyle1207@gmail.com)
- Github - [Lê Mạnh Đan](https://github.com/DanKRT-Star)

## Acknowledgments

Thanks to Frontend Mentor and the community for providing helpful resources and feedback during this challenge.