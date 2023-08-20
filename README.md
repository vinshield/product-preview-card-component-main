# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot 2023-08-20 at 18-28-18 Frontend Mentor Product preview card component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt how to think of a card component more wholistically, utilizing features like grid gap and custom properties to avoid repitition and write neater, more orderly code. I'm glad I practiced the use of custom properties in particular. The benefit of this really comes to play in larger projects because custom properties make the css much easier to manage.

I also learnt to use hidden html elements to provide important information for screen readers and assitive technologies, while ensuring that they don't appear on screen. Here is the css I used for that:

```
.visually-hidden:not(:focus):not(:active) {
	clip: rect(0 0 0 0);
	clip-path: inset(50%);
	height: 1px;
	overflow: hidden;
	position: absolute;
	white-space: nowrap;
	width: 1px;
}

```

### Useful resources

- [Kevin Powell Video](https://www.youtube.com/watch?v=B2WL6KkqhLQ&ab_channel=KevinPowell) - Shoutout to Kevin Powell! He takes a lot of care to make his videos engaging, resourceful and easy to understand. 
- [Article by Scott O'Hara](https://www.scottohara.me/blog/2017/04/14/inclusively-hiddena.html) - This article (recommended by Kevin Powell) provided the css for visually hidden divs.

## Author

- Website - [Jesse](https://www.your-site.com)
- Frontend Mentor - [@vinshield](https://www.frontendmentor.io/profile/vinshield)
- Twitter - [@jeslelacodes](https://www.twitter.com/jeslelacodes)
