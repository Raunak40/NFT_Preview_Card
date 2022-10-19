# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/Desktop-preview.png.jpg)
![](./design/Mobile-preview.png.jpg)

### Links

- Solution URL: [Github](https://github.com/Raunak40)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The difficult part was to program the view icon of the ethereum card. During this process I found some new pseudo elements namely ```:first-child``` and ```:last-child```.

```css
.eth-card img:first-child{
    border-radius: 1em;
}

.eth-card img:last-child{
    display: none;
}
```

### Continued development

Will try to make the CSS more readable and develepor freindly by reducing the amnount of code.


## Author

- Website - [Raunak Raj](https://www.your-site.com)
- Frontend Mentor - [@Raunak40](https://www.frontendmentor.io/profile/Raunak40)
- Github - [@Raunak40](https://github.com/Raunak40)

