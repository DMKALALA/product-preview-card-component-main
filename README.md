# Frontend Mentor - Product preview card component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
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

### Screenshot

### None

### Links

- Solution URL: (https://github.com/DMKALALA/product-preview-card-component-main)
- Live Site URL: (https://github.com/DMKALALA/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid

### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used.
Always open to any comments

```css
body {
  font-family: var(--ff-body);
  font-weight: var(--fw-regular);
  font-size: 0.875rem;
  color: var(--clr-neutral-400);
  background-color: var(--clr-secondary-200);

  display: grid;
  gap: 8rem;
  place-content: center;
  margin: 1rem;
}

.attribution {
  text-align: center;
}

.attribution a {
  color: var(--clr-primary-400);
}

.Price__group {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap; /*to prevent overlapping*/
  align-items: center;
}

.product {
  /*It is easier to work with variables in the product class rather than looking everywhere for it*/
  --content-padding: 1.5rem;
  --content-spacing: 0.5rem;
  display: grid;
  background-color: var(--clr-neutral-100);
  border-radius: 0.5rem;
  overflow: hidden;
  max-width: 600px;
}

.product__content {
  padding: var(--content-padding);
  /* display: flex;
    flex-direction: column; */
  display: grid;
  gap: var(--content-spacing);
}
```

### Continued development

I would like to make my own QR Generator so this could be used as a default template.

The qr code could be links to a document or something along those ways. Going to think about something useful that could come in handy.

### Useful resources

- [FLEXBOX FROGGY](https://flexboxfroggy.com/#es) - This helped me to understand better how to use flexbox.

- [KEVIN POWELL](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=609s&pp=ygUeUHJvZHVjdCBwcmV2aWV3IGNhcmQgY29tcG9uZW50) This was the main resource used to fill any gaps in my knowledge.

## Author

- Frontend Mentor - [@DMKALALA](https://www.frontendmentor.io/profile/DMKALALA)

## Acknowledgments
