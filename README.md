# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

This component was to get me back into coding again after a 2yr absence. I enjoyed practing and re-establishing my HTML & CSS layout skills again.

### Screenshot

![](./qr-code-screenshot.png)

### Links

- Solution URL: [FEM Solution Link](https://www.frontendmentor.io/solutions/responsive-qr-card-component-using-css-variables-zDUPcZiuy)
- Live Site URL: [Deployed Project Link](https://brianj-27.github.io/QR-Card-Component/)

## My process

My process for this project was first getting my HTML structure correct and make sense. Within my main tag, I first created a div with a card class which will control the width of the card. Afterwards, I decided to use figure tag along with a figcaption tag because to me it semantically made sense because of the image and the accompanying content right under it. Next, I added my normalize stylesheet and my main stylesheet.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to work with CSS custom properties. This was my first time working with them ever... I am still learning the best way to take advantage of them. Also I learned about using figure and figcaption elements properly in this project. Also in my css, it was my first taste in use the min() on my card class

To see how you can add code snippets, see below:

Using more semantic elements like figure and figcaption

```html
<figure>
  <img src="./images/image-qr-code.png" alt="QR Code Design" />
  <figcaption>
    <h1>
      <strong>Improve your front-end skills by building projects</strong>
    </h1>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </figcaption>
</figure>
```

Using the min() for the first time!

```css
.card {
  background: var(--card-color-white);
  width: min(100%, 350px);
  margin: auto;
}
```

### Continued development

I want to continue getting more comfortable with using custom properties and exploring how to maximize their power. Also, this project was a simple HTML layout. I want to make sure I am giving more attention to HTML structure so my css will be easier to code out. I purposely left out Sass in this project because of the simplicity of it. For future projects, I will start using it more.

### Useful resources

- [Developer Mozilla: min() MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/min) - This helped me understand the basics of using the min() and how to implement it
- [Kevin Powell's Youtube Video on Using Min() Max() & clamp()](https://www.youtube.com/watch?v=U9VF-4euyRo&t=874s) - This is Kevin Powell's amazing video tutorial which helped me to visually follow along and learn the basics. I'd recommend it to anyone still learning this concept.

## Author

- My Website - [Brian's Website](https://brianbjohnson.net/)
- Frontend Mentor Profile - [@BrianJ-27](https://www.frontendmentor.io/profile/BrianJ-27)
