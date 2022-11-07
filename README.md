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
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: https://github.com/Faris-Thibani/Profile-Card
- Live Site URL: https://faris-thibani.github.io/Profile-Card/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I gained some new insights on the background-image property or it's ability to take in two values.

Also proud about remmembering to use the list element.
```html
<ul class="stats-list flex">
      <li class="item">
        <p class="number">
          80K
          <span class="darkGrey stat">
            Followers
          </span>
        </p>
      </li>
      <li class="item">
        <p class="number">803K
          <span class="darkGrey stat">
            Likes
          </span>
        </p>
      </li>
      <li class="item">
        <p class="number">
          1.4K
          <span class="darkGrey stat">
            Photos
          </span>
        </p>
      </li>
    </ul>
```
```css
.wrapper{
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-image:
    url(../images/bg-pattern-top.svg),
    url(../images/bg-pattern-bottom.svg);
    background-repeat: no-repeat;
    background-position: right calc(47vw + 24%) bottom calc(65vh - 15vw),
    left calc(40vw + 25%) top calc(72vh - 10vw);
    background-color: var(--darkCyan);
    text-align: center;
}
```




## Author


- Frontend Mentor - [@Faris-Thibani](https://www.frontendmentor.io/profile/Faris-Thibani)

