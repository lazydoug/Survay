# Survay
A survey form to collect data from users.

# freeCodeCamp Certification Project solution

## Table of contents
- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
This is my first challenge on Frontend Mentor. I took on this challenge so as to improve and test my skills as a aspiring Frontend Developer.

### Screenshot
- Solution screenshot: (./screenshot.png)

### Links
- Solution URL: (https://lazydoug.github.io/Survay/)

## My process

### Built with
- HTML
- CSS

### What I learned
I can better structure forms, using the proper html elements (label, input, select, etc.) and attributes (required, max, min, maxlength, etc.). I practiced using parallax scrolling on a background image.

```html
<fieldset>
...
  <label id="email-label">Email <input id="email" type="email" placeholder="Enter your Email" required /></label>
  <label id="number-label">Age (optional) <input id="number" type="number" placeholder="Age" min="10" max="99" /></label>
...
```

```css
body {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  ...
}

.content {
  ...
  margin: auto;
  }
```

## Author
- Linkedin - (https://www.linkedin.com/in/id-douglas/)
- Frontend Mentor - [@lazydoug](https://www.frontendmentor.io/profile/lazydoug)
- freeCodeCamp - (https://www.freecodecamp.org/lazydoug)
