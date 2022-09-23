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

![](images/SolutionScreenShot.png)

This is a screenshot of my solution.


### Links

- Solution URL: [Solution](https://github.com/Kmchenry70/qr-code-component-main)
- Live Site URL: [Live site](https://your-live-site-url.com)


## My process


### Built with

- Non-Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox


### What I learned

From this project, I learned how to use CSS Flexbox to manipulate items within the container div.

```css
.qr-container {
    background-color: hsl(0, 0%, 100%);
    width: 18%;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
    /* top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); */
}
```
I also learned another way to center container divs in CSS using the transform property.

```css
.qr-container {
    /* background-color: hsl(0, 0%, 100%);
    width: 18%;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute; */
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```


### Continued development

I want to continue to get more fluent in HTML and CSS.


### Useful resources

- [w3schools](https://www.w3schools.com/) - This helped me reference different CSS properties and explained flexbox.

## Author

- Github - [Kmchenry70](https://github.com/Kmchenry70)
- Frontend Mentor - [@Kmchenry70](https://www.frontendmentor.io/profile/Kmchenry70)


