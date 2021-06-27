# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview
here is my solution for the callenge from Frontend Mentor | Profile card component, learned alot about positioning in this one . 
### The challenge

- Build out the project to the designs provided

### Screenshot

![](/images/completed.JPG)


### Links

- Solution URL: [https://github.com/anas-cd/profile-card-component](https://github.com/anas-cd/profile-card-component)
- Live Site URL: [https://anas-cd.github.io/profile-card-component](https://anas-cd.github.io/profile-card-component/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS position property 


### What I learned

* I learned alot about positioning for example, making a responsive view using the fixed position and top, right, bottom and left properties, like in the following code where the two background svgs gets to be responsive without affecting the profile card, like this :


```css
&.topl { 
            z-index: -1;
            top: -60%;
            right: 48%;
        }
```
also the svg on the left gets positioned from the right and vice versa to get the responsiveness effect

---------- 
* the secnod thing I learnd was a trick to make the card centered horizontally using align-item without shrincking the card's size, and that's simply specifing the width to be 100% along with the max-width of the card like so : 

```css
.container { 
    display: flex;
    flex-direction: column; /*since this is a column, align wont work normally so we need to specify the width as well to 100% */
    justify-content: center;
    align-items: center;
}

main {
    max-width: 350px;
    height: 374px;
    flex-direction: column;
    width: 100%; /* like so */
}
```

### Continued development

will see if there is any other way to center the card without using the width 100% trick 


## Author

- Website (still working on it) - [Anas Ali](https://anas-cd.github.io/)
- Frontend Mentor - [@anas-cd](https://www.frontendmentor.io/profile/anas-cd)
- Twitter - [@AnasCd](https://www.twitter.com/AnasCd)

## Acknowledgments
I used a really helpfull and simple boilerplate made by "coder-coder" for frontend development, here is the repo for it : 

- coder-coder - [biolerplate](https://github.com/thecodercoder/frontend-boilerplate)
