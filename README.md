# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202023-05-15%20124908.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/3columnpreviewcard-p_5KeRn4wj](https://www.frontendmentor.io/solutions/3columnpreviewcard-p_5KeRn4wj)
- Live Site URL: [https://tahobbit11.github.io/3-column-preview-card/](https://tahobbit11.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use flexbox to change the display of the content.

```html
      <div class="sedan-wrapper">
        <div class="sedan-content">
          <img src="./images/icon-sedans.svg" alt="sedan-img">
          <h1>Sedans</h1>
          <p>
            Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city 
            or on your next road trip.
          </p>
        </div>
        <div>
          <button class="sedan-button">Learn More</button>
        </div>
      </div>
```
```css
    .content-wrapper {
      width: 920px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: row;
      margin-top: 12.5%;
    }
```

## Author

- Frontend Mentor - [@tahobbit11](https://www.frontendmentor.io/profile/tahobbit11)
