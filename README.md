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
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- [Solution URL](https://github.com/JaidanBrown/fm-qr-code-component)
- [Live Site](https://jaidanbrown.github.io/fm-qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I tried to use accessible UX design with the inclusion of an alt tag to accomodate for all users of the site. I am still learning about about accessiblility. It is a topic I am always learning new methods and techniques about.

```html
<img
	src="images/image-qr-code.png"
	alt="QR code image linking to frontend mentor site"
/>
```

I also used CSS custom properties in this too improve the scaleability of the project. It is alot easier to change one color variable than have to change 20!

```css
:root {
	--clr-white: hsl(0, 0%, 100%);
	--clr-light-gray: hsl(212, 45%, 89%);
	--clr-grayish-blue: hsl(220, 15%, 55%);
	--clr-dark-blue: hsl(218, 44%, 22%);

	--weight-400: 400;
	--weight-700: 700;
}
```

### Continued development

If I were to continue the development of this project, I could make a QR code generator application.

## Author

- Website - [Jaidanbrown.dev](https://jaidanbrown.dev)
- Frontend Mentor - [@JaidanBrown](https://www.frontendmentor.io/profile/JaidanBrown)
