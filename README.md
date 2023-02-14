# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
@media only screen and (max-width: 768px) and (min-width: 426px) {
  body {
    font-size: 12px;
  }

  .text-component {
    padding: 12%;
  }

  .title {
    font-size: 22px;
  }

  ul {
    padding-top: 30px;
  }

  ul li {
    font-size: 17px;
  }
}

@media only screen and (max-width: 425px) {
  body {
    text-align: center;
  }

  .wrapper {
    grid-template-columns: 1fr;
  }

  .img-component {
    order: -1;
  }

  .text-component {
    padding: 12% 8%;
  }

  .title {
    font-size: 23px;
    line-height: 1.4;
  }

  ul {
    flex-direction: column;
    padding-top: 30px;
  }

  ul li {
    margin-top: 20px;
  }
}
```
