# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot](app/assets/images/Screenshot%202023-11-04%20%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL](https://resilient-pie-e4d105.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Sass/scss

### What I learned

Beginning to see a viable workflow emerge. Mobile first for the styling; then desktop for the layout. The tricky part was getting the cards to behave.
I had to do a few experiments on the side while I allowed the mobile version to chill. These experiments allowed me to get a grip on overlapping grid items using negative margins.
Lastly, when it was time to incorporate the grid into the design, I switched from naming the columns / rows explicitly and was ablw to get grid-template-area to work.

```css
main {
  display: grid;
  gap: 20px;
  grid-template-areas:
    "red cyan orange"
    "red blue orange";
}
.red {
  grid-area: red;
}
.cyan {
  grid-area: cyan;
}
.orange {
  grid-area: orange;
}
.blue {
  grid-area: blue;
}
```

### Continued development

I still need to learn box-shadow (I stole the one I used here from a box-shadow-generator)

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/beowulf1958)
