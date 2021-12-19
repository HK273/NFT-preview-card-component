# Frontend Mentor - NFT preview card component

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

NFT card design

### Links

- [Solution URL]()
- [Live Site URL]()

### Built with

- HTML5
- Flexbox

### What I learned

- Spacing flex items
- Animation affects
- using ::before to allign icons

```css
/* icon inline with text */
.icon_one::before {
  content: url(/images/icon-ethereum.svg);
  margin-right: 0.8rem;
  /* centre icon */
  vertical-align: middle;
}
```

```css
/* small animation on img hover */

img:hover {
  transform: rotateY(180deg);
}
```

### Useful resources

- [Align icons to text](https://stackoverflow.com/questions/31296276/how-to-align-text-next-to-an-icon-with-css/31296396)
- [Centre icon](https://coryrylan.com/blog/css-gap-space-with-flexbox)

## Author

- Frontend Mentor - [@HK273](https://www.frontendmentor.io/profile/HK273)
