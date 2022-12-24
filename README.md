# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop](https://raw.githubusercontent.com/GHWhite419/Huddle-landing-page-coding-challenge/main/screenshots/Desktop.png)
![Mobile](https://raw.githubusercontent.com/GHWhite419/Huddle-landing-page-coding-challenge/main/screenshots/Mobile.png)
![Tablet portrait](https://raw.githubusercontent.com/GHWhite419/Huddle-landing-page-coding-challenge/main/screenshots/Tablet portrait.png)
![Tablet landscape](https://raw.githubusercontent.com/GHWhite419/Huddle-landing-page-coding-challenge/main/screenshots/Tablet landscape.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/huddle-landing-page-with-a-single-introductory-section-OSqNYO4zhr)
- Live Site URL: (https://ghwhite419.github.io/Huddle-landing-page-coding-challenge/)

## My process

I began with the bulk of the HTML markup before beginning the styles in CSS. After first completing the mobile version I took on the desktop view next, tweaking some HTML markup as I went. Once satisfied with how it looked on the desktop version, I did a final couple of passes to ensure everything looked right on mobile landscape and tablet views.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Fontawesome SVGs (https://fontawesome.com)

### What I learned

This project was another opportunity to practice using SVG images and coloring them via filters. Here's what I used:

```html
      <div class="share">
        <div class="icon"><img src="images/facebook-f.svg" aria-hidden="true"></div>
        <div class="icon"><img src="images/twitter.svg" aria-hidden="true"></div>
        <div class="icon"><img src="images/instagram.svg" aria-hidden="true"></div>
      </div>
```
```css
.share {
  display: flex;
  flex-direction: row;
  justify-content: center;
  margin: 6rem 0rem -1rem 0rem;
}

.icon {
  border-radius: 100%;
  border: 1px solid black;
  padding: .5rem;
  filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(211deg) brightness(106%) contrast(104%);
  margin: 0rem .5rem;
}

.icon:hover {
  filter: invert(55%) sepia(95%) saturate(2580%) hue-rotate(262deg) brightness(88%) contrast(98%);
}

.icon img {
  width: 1rem;
  height: 1rem;
}
```

## Author

- Frontend Mentor - [@JudasThePriest](https://www.frontendmentor.io/profile/JudasThePriest)
