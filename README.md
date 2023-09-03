# Frontend Mentor - News homepage

![Design preview for the News homepage coding challenge](./design/desktop-preview.jpg)

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Github page](https://jositu.github.io/fm-news-homepage/)

## My process

<!-- `8hr` -->

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Javascript
- CSS Grid
- [Normalize.css](https://necolas.github.io/normalize.css/) - CSS reset for more consistent styling throughout different browsers

### What I learned

I started developing this design with a Desktop-first workflow because the grid layout of the desktop design was much more complex than the mobile design's.

I recently learned about utility classes. Even though this is a rather small project, which probably does not require the amount of utility classes I wrote for it, I put a lot of effort into creating thorough utility classes in order to reinforced what I've learned.

Practice CSS grid

Using em for breakpoints vs pixel-based breakpoints

instead of setting my custom color properties with actual values in hsl format, such as:

```css
:root {
  --clr-orange: hsl(35, 77%, 62%);
}
```

Setting the property as ONLY the number values, such as the example below, is much more useful. This way I can adjust the opacity of this color whenever I use the variable elsewhere in my CSS.

```css
:root {
  --clr-orange: 35, 77%, 62%;
}

#primary-nav-background {
  background-color: hsl(var(--clr-very-dark) / 0.4);
}
```

Practiced using aria attributes in my code.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
