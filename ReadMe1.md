# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

First Attempt:
![Screenshot first attempt Stats Preview Card Component.png](images/Screenshot%20first%20attempt%20Stats%20Preview%20Card%20Component.png)
______________________

Second Attempt and Final Submission:
![Screenshot 2025-07-05 at 12-26-27 2nd Stats Preview Card Component.png](Screenshot%202025-07-05%20at%2012-26-27%202nd%20Stats%20Preview%20Card%20Component.png)


![Screenshot 2025-07-05 at 12-27-15 2nd Stats Preview Card Component.png](Screenshot%202025-07-05%20at%2012-27-15%202nd%20Stats%20Preview%20Card%20Component.png)




### Links

- Solution URL: [[Add solution URL here](https://github.com/StiTchD-WireD/P1-Stats-preview-card-component)
- Live Site URL: [Add live site URL here](https://stitchd-wired.github.io/P1-Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned

1. Image: Adding a color overlay to an image, and adjusting hsl, opacity and contrast.
2. Planning and using div classes.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
/* Image*/

.image-column {
  position: relative;
  display: flex;
  justify-items: center;
  align-items: center;
  width: 50%;
  height: fit-content;
  filter: contrast(1.5) brightness(0.8) saturate(0.8);
  overflow: hidden;
  overflow-clip-margin: 20px;
}

/* purple overlay filter*/

.image-column::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: hsl(277, 60%, 50%);
  opacity: 0.55;
}
```


### Continued development

Practice positioning and control of images, e.g. using a % to allow for responsive design but not to the negative effect of any neighboring boxes.

### Useful resources

- [W3 Schools](https://www.example.com) - Offers a description of various attributes and functions and allows for testing each one in a small activity.
- [Youtube] - Helped me with the colour overlay on the image. Introduced me to ::before / ::after. 

## Author

- Website - [Stitch](https://stitchd-wired.github.io/P1-Stats-preview-card-component/)
- Frontend Mentor - [@StiTchD-WireD](https://www.frontendmentor.io/profile/StiTchD-WireD)








