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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

#### Desktop view
![](./images/full-page-to-readme.png)

#### Mobile view
![](./images/full-page-to-readme-mobile.png)

### Links

- Solution URL: [HTML & CSS Code](https://github.com/oihenrique/frontend-mentor-challenges/tree/main/01.%20%5Bhtml-css%5D%20Stats%20Preview%20Card%20Component)
- Live Site URL: [Live site visualization](https://oihenrique.github.io/frontend-mentor-challenges/01.%20[html-css]%20Stats%20Preview%20Card%20Component/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project, I learned about how to positioning elements with Flexbox, using the ```justify-content``` and the ```flex-direction```.

```css
.container {
    display: flex;
    justify-content: space-between;
}
```
```css
@media (max-width: 991px) {
  .container {
      flex-direction: column-reverse;
  }
}
```

### Continued development

- I want to continue learning about Flexbox, I still have trouble positioning the elements on the page. 

- I need more practice to fix HTML tags and how the &lt;div&gt; inside another &lt;div&gt; are related each other.

- I need to practice responsivity and the mobile pages development, I had trouble trying to fix the main container size and the image inside of it.

### Useful resources

- [MDN - Basics of Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - This helped me to learn how Flexbox works.
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/) - I used this site to research HTML tags, CSS properties and Flexbox.

## Author

- Github - [My github profile](https://github.com/oihenrique)
- Frontend Mentor - [@oihenrique](https://www.frontendmentor.io/profile/oihenrique)
- Linkedin - [Mu linkedin profile](https://www.linkedin.com/in/oihenriquegomes/)