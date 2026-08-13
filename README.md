# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [GitHub Repository](https://github.com/marek-milacek/frontendmentor-four-card-feature-section)
- Live Site URL: [Netlify Live Site](https://frontendmentor-four-card-feature123.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I learned how to use **CSS Grid** to create a custom 3-column desktop layout where cards are placed in specific grid cells using `:nth-child()` selectors, `grid-column`, and `grid-row`.

I also learned how to vertically center cards in grid cells with `align-self: center;` and how to control text wrapping using `max-width`.

Example CSS Grid placement used in the solution:
```css
.card:nth-child(1) {
    grid-column: 1;
    grid-row: 1 / 3;
    align-self: center;
}
```

### AI Collaboration

Used Google Antigravity as an AI mentor to guide me step-by-step through CSS Grid concepts, line numbering, and targeting elements with `:nth-child()` selectors.

## Author

- GitHub - [Marek Miláček](https://github.com/marek-milacek)
