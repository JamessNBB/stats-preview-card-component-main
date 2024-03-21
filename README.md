# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot
![Desktop-view](screenshots/desktop-view.png)

![Mobile-view](screenshots/mobile-view.png)


### Links

- Solution URL: [Solution](https://github.com/JamessNBB/stats-preview-card-component-main.git)
- Live Site URL: [Live site](https://jamessnbb.github.io/stats-preview-card-component-main/)

## My process

### Built with

- HTML5
- CSS
- CSS Grid

### What I learned

I was able to refresh and refine my understanding of CSS grid layout. I recently learned font shorthand, so I was able to practice and apply it in this project, see extract below:
```css
#paragraph-main {
  font: 400 15px/1.66 'Inter';
  color: var(--slightly-transparent-white-main-paragraph);
  margin: 1.65rem 0 4.45rem 0;
  max-width: 350px;
}
```
I was also able to refresh memory on how to automatically change images based on screen size using media query.
```html
<div class="image-area">
        <picture>
          <source srcset="images/image-header-mobile.jpg" media="(max-width:1021px)">
          <img src="images/image-header-desktop.jpg" alt="">
          <div class="overlay"></div>
        </picture>
```


### Continued development

I tried 2 ways of using the CSS grid layout: 1. gid-template-areas and 2. gird-template-cplumns.  Unfortunately I struggled a lot with utilizing the gird-template-areas, so I had to abandon it and use the grid-template-colums format which was quite straight forward and easy to understand to me. 

That being said, I would like to improve and develop more on the use of the various CSS layout methods whether it's flexbox, grid, or any other type. I would also like to develop and perfect my skills on web responsiveness.


### Useful resources

[W3Schools](https://www.w3schools.com/) - Excellent place to get you started on your programming journey. It helped me understand some basic HTML elements and CSS properties.


## Author

- GitHub - [James](https://github.com/JamessNBB)
- Frontend Mentor - [@JamessNBB](https://www.frontendmentor.io/profile/JamessNBB)


## Acknowledgments

I was able to complete this project by myself, but I want to appreciate [Frontend Mentor](https://www.frontendmentor.io) for giving the opportunity to improve my coding skills by doing challenges such as this.