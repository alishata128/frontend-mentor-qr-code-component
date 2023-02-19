# Frontend Mentor - QR code component solution

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

![](./images/QR%20code%20component%20desktop.png)
![](./images/QR%20code%20component%20mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variable
- Flexbox
- CSS Flex
- Mobile-first workflow
- Chrome Developer Tools

### What I learned

I made a revision on css variables and how to decrease the opacity of a color if it in hsl syntax and got to know a great font by the name of Outfit, it's a great font which I'll Integrate it to my own designs and build also learnt about the relation between width and padding and margin, and for the sake of aligning some elements to the top and other on the center I came across the margin auto propery

```css
:root {
  --bluish-black: hsl(218, 44%, 22%);
  --white: hsl(0, 0%, 100%);
  --light-gray: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
}

body{
  font-family: "Outfit", sans-serif;
  }
  .attribution{
      margin-bottom: auto;
  }
```
### Continued development

I want to continue focusing on creating this project as a component in react I think it well be great to implement
it in my react projects, I think I'm not comfortable with colors because whenever I need to pick a colors I go to Abode Color or any color palettes providers and getting lost between the palettes, I found the technique of CSS Variables is very practical and could do a great role in dark mode switching situation.

### Useful resources

- [w3schools in CSS Variables](https://www.w3schools.com/css/css3_variables.asp) - This helped me for setting the colors you provided in variables.
- [w3schools in margin auto](https://www.w3schools.com/css/css_margin.asp) - This helped me to get to know the auto property and how it can be used in most aligning situations

## Author

- Website - [Ali Shata](https://www.linkedin.com/in/alishata)
- Frontend Mentor - [@alishata128](https://www.frontendmentor.io/profile/alishata128)
- Twitter - [@alishata128](https://www.twitter.com/alishata128)
