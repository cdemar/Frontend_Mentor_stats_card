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

![](/dist/images/screenshot.jpg)

### Links

- Solution URL: [solution here](https://github.com/cdemar/Frontend_Mentor_stats_card)
- Live Site URL: [live site here](https://cdemar.github.io/Frontend_Mentor_stats_card/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Grid
- Mobile-first workflow

### What I learned

Something that I have always struggled on is letting an image be shown when on the website, because it's different when I need to do it on my local computer. I also used SCSS for only the second time, but the first time was mainly copying and pasting from a website I used only CSS with.


```html
  <div class="card__picture">
    <div class="card__overlay"></div>
  </div>
```

When live.
```css
.card__picture {
  background-image: url(./../../dist/images/image-header-mobile.jpg);
}
```
When on my computer
```css
.card__picture {
  background-image: url(./../dist/images/image-header-mobile.jpg);
}
```

Besides that I learned how to use grid. Below are a few examples I used.
```css
body {
  display: -ms-grid;
  display: grid;
}

.card {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (1fr)[1];
      grid-template-columns: repeat(1, 1fr);
```

### Continued development

I definitely still want to focus more of my time with using grid, but also trying to figure out when it is better to use grid vs. flexbox.

### Useful resources

- [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This was a great resource when trying to learn about 'Grid'. This is a site I use often when wanting to learn something new.

- [CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This website is similar to Mozilla in the format of using it when needing to learn something new.

- [SCSS](https://sass-lang.com/documentation/syntax) - I also got a lot of information from how to set up a lot of my SCSS in a strong way.

## Author

- Website - [Cory D.](https://www.your-site.com)
- Frontend Mentor - [@cdemar](https://www.frontendmentor.io/profile/cdemar)
- Twitter - [@thecdemar](https://twitter.com/thecdemar)

## Acknowledgments
My family is the biggest inspiration for me to do these and to grow more as a programmer to make a better life for myself and for them. Besides that [Jessica Chan](https://www.youtube.com/watch?v=aoQ6S1a32j8&t=13825s)'s video on [freeCodeCamp.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) YouTube channel was also a large inspiration to not only practice my SCSS but also try a new way of programming by using grid.
