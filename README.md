# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Four card feature section solution](#frontend-mentor---four-card-feature-section-solution)
  - [Table of contents](#table-of-contents)
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

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)
### Links

- Solution URL: [https://github.com/KrzysztofGrudzien/frontend-mentor-four-card-feature-section](https://github.com/KrzysztofGrudzien/frontend-mentor-four-card-feature-section)
- Live Site URL: [https://krzysztofgrudzien.github.io/frontend-mentor-four-card-feature-section/](https://krzysztofgrudzien.github.io/frontend-mentor-four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM Methodology
- Mobile-first workflow

### What I learned

Basic knowledge about HTML, CSS, Flexbox, Custom properties and BEM methodology.

```html
        <main class="main">
            <section class="feature">
                <h1 class="feature__title">Reliable, efficient delivery</h1>
                <p class="feature__slogan">Powered by Technology</p>
                <p class="feature__description">
                    Our Artificial Intelligence powered tools use millions of project data points to ensure that your
                    project is successful
                </p>
                <div class="feature__cards">
                    <article class="card card--cyan">
                        <h2 class="card__title">Supervisor</h2>
                        <p class="card__description">Monitors activity to identify project roadblocks</p>
                        <img src="./images/icon-supervisor.svg" alt="" class="card__img" />
                    </article>
                    <div class="divider">
                        <article class="card card--red">
                            <h2 class="card__title">Team Builder</h2>
                            <p class="card__description">
                                Scans our talent network to create the optimal team for your project
                            </p>
                            <img src="./images/icon-team-builder.svg" alt="" class="card__img" />

```
```css
    .feature__description {
        margin: 1rem auto 4.75rem auto;
        width: 50%;
    }

    .feature__cards {
        align-items: center;
        display: flex;
        justify-content: space-between;
    }

    .feature__cards div {
        margin: 0 2rem;
        width: 100%;
    }

    .card {
        min-height: 250px;
        width: 100%;
    }

    .feature__cards div > .card {
        margin-bottom: 2rem;
    }

    .card__img {
        bottom: 2rem;
        height: 64px;
        position: absolute;
        right: 2rem;
        width: 64px;
    }
```
## Author

- Website - [In progress]
- Frontend Mentor - [@KrzysztofGrudzien](https://www.frontendmentor.io/profile/KrzysztofGrudzien)
- E-mail - krzysztof.grudzien.fed@gmail.com
