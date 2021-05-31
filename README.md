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

![](design/finished-card.png)

### Links

- Solution URL: [https://github.com/CrazedDoggo/FEM-ProfileCardComponent](https://github.com/CrazedDoggo/FEM-ProfileCardComponent)
- Live Site URL: [https://crazeddoggo.github.io/FEM-ProfileCardComponent/](https://crazeddoggo.github.io/FEM-ProfileCardComponent/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

The pain of having to position multiple elements that flow well in different layouts. I experimented and managed to find a solution decent enough, with my first attempts being:

- Using background images and then positioning them (led to a disconnect between mobile and desktop)
- Translating (also led to a disconnect between mobile and disconnect)

I *could've* use media queries, but the transition wasn't the smoothest and I wanted to find a way to position them in a simple manner. I finally settled on absolute positioning, but I still had one issue. After positioning them where all looked well, upon going to mobile-view there was a large amount of overflow. Even after hiding overflow, it still remained.

 I tried positioning the body to relative which did not assist, and after plugging in values it seems that setting the body's position to fixed removed all the overflow. I believe this is because it fixes the body to the viewport's width and height, disallowing it to overflow regardless.

## Author

- GitHub - [Crazed Doggo](https://www.your-site.com)
- Frontend Mentor - [@CrazedDoggo](https://www.frontendmentor.io/profile/CrazedDoggo)
