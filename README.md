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

![](images/product-preview-card-component.jpg)

### Links

- Solution URL: [GitHub](https://github.com/ebenezerraph/product-preview-card-component/)
- Live Site URL: [Product Preview Card Component](https://ebenezerraph.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned how to make the design responsive using Flexbox. I was able to display different images based on the device's screen.

```HTML
<picture>
    <source srcset="images/image-product-mobile.jpg" media="(max-width: 700px)">
    <source srcset="images/image-product-desktop.jpg">
    <img class="product-image" src="images/image-product-desktop.jpg" alt="product-image">
</picture>
```
```css
@media screen and (max-width: 700px) {
    .flex-container {
        display: flex;
        flex-direction: column;
        width: 343px;
    }
```

### Useful resources

- [HTML & CSS: Design and Build Web Sites - Book by Jon Duckett](https://www.htmlandcssbook.com/) - This helped me address minor issues in my code. And I will continue using it.
- [W3Schools](https://www.w3schools.com/) - This is where I learned how to make the web page responsive.

## Author

- GitHub - [@ebenezerraph](https://www.github.com/ebenezerraph)
- Frontend Mentor - [@ebenezerraph](https://www.frontendmentor.io/profile/ebenezerraph)
- Twitter - [@ebenezerraph](https://www.twitter.com/ebenezerraph)
