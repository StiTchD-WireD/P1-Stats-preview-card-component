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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

First Attempt:
![Screenshot first attempt Stats Preview Card Component.png](images/Screenshot%20first%20attempt%20Stats%20Preview%20Card%20Component.png)
______________________

Second Attempt and Final Submission:
![ScreenshotPreview%20Card%20Component.png] (Screenshot%202025-07-05%20at%2012-26-27%202nd%20Stats%20Preview%20Card%20Component.png)


[[ScreenshotPreview%20Card%20Component.png](https://github.com/StiTchD-WireD/P1-Stats-preview-card-component/blob/f9d55097388040d3173879e3d81c6d896e1ad66b/Screenshot%202025-07-05%20at%2012-26-27%202nd%20Stats%20Preview%20Card%20Component.png))](https://github.com/StiTchD-WireD/P1-Stats-preview-card-component/blob/2nd-Stats-Preview-Card-Component.html/Screenshot%202025-07-05%20at%2012-27-15%202nd%20Stats%20Preview%20Card%20Component.png)




### Links

- Solution URL: [[Add solution URL here](https://github.com/StiTchD-WireD/P1-Stats-preview-card-component)](https://stitchd-wired.github.io/P1-Stats-preview-card-component/)
- Live Site URL: [Add live site URL here](https://stitchd-wired.github.io/P1-Stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


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

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)


**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**



