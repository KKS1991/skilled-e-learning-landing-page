# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The Challenge was to build out a landing page and get it looking as close to the design as possible.

It was possible to use any tools to complete the challenge.

Your users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop-Version](/screenshots/ss_desktop.jpg)

### Links

- Solution URL: [My Solution](https://kks1991.github.io/skilled-e-learning-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Bootstrap] (https://getbootstrap.com/) - Bootstrap framework

### What I learned

Good things during the project

- I've build a good HTML markup within a few hours
- I was persistent and worked on the project even there were heavy party/days
- I've learned a lot about the the funktions of frondentmentor.io, the slack community and Git/GitHub
- I've learned that doesn't exist one solution. There are a few ways to solve a challenge.

Doesn't match my expectations

I've also learned that CSS-Grid isn't appropriate for me to build a header or footer. I've tried to build the header with CSS-Grid but it caused some issues with the `<img>` at the bigger screensizes. Regarding the `<img>` - it caused some issues farther if you zoom out because of the

```CSS
.hero__img {
  position: absolute;
  right: -15rem;
  top: -14rem;
}
```

A additinal issue i see here

```CSS
#hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 1rem;
  margin-bottom: 0;
  padding: 1rem 1rem;}
```

I centered the cards in the CSS-Grid-Container to avoid an overflow/scrolling on the right side. Otherwise they doesn't match on the screensize. Now the doesn't match in the CSS-Grid-Container.
`

## Author

- Website - [Kevin Schupp](https://www.kevinschupp.de/)
- Frontend Mentor - [@KKS1991](https://www.frontendmentor.io/profile/KKS1991)
- Instagram - (https://www.instagram.com/kks1991/)
- Xing (https://www.xing.com/profile/Kevin_Schupp3)
- Linkedin (https://www.linkedin.com/in/kevin-schupp-968a5a162/)

## Acknowledgments

I want to thank [@a-woodworth] for charing his solutions. His Code helped me a lot to fix my issues. =)
