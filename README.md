# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- View the optimal layout for the interface depending on their device's screen size.

### Screenshot

![Screenshot](![image](https://github.com/user-attachments/assets/c34efa3f-1fde-498c-b480-c4926386f807)
)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I enhanced my understanding of **CSS Grid** and its flexibility in creating dynamic layouts. I also practiced responsive design techniques with media queries to ensure a seamless experience across various screen sizes.

Here's an example of the CSS I used to create the grid layout:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

@media (max-width: 768px) {
  .grid-container {
    grid-template-columns: repeat(2, 1fr);
  }
}
```

### Continued development

Moving forward, I plan to dive deeper into:

- Advanced **CSS Grid techniques**.
- Improving accessibility by ensuring all elements are navigable via keyboard and screen readers.
- Working with **CSS animations** to enhance user experience.

### Useful resources

- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This is the official documentation on CSS Grid and it helped me understand grid layout properties better.
- [CSS Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - A comprehensive guide to CSS Grid, which was invaluable when implementing the grid layout for this challenge.

## Author

- Website - [Chandu Pichika]((https://pichikachandu.netlify.app/))
- Frontend Mentor - [@ChanduPichika](https://www.frontendmentor.io/profile/ChanduPichika)
- GitHub - [@ChanduPichika](https://github.com/ChanduPichika)

## Acknowledgments

Thanks to **Frontend Mentor** for providing this great challenge. It has been a valuable learning experience and I look forward to completing more challenges to further sharpen my skills.
![image](https://github.com/user-attachments/assets/5be82f04-6d88-4926-8e67-af6b14ac187e)
