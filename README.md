<!-- Please update value in the {}  -->

<h1 align="center">Shoe Product Page | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/simple-product-page-challenge" target="_blank">Shoe Product Page</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://mlvoorhis.github.io/shoe-product-page-master/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/mlvoorhis/shoe-product-page-master">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/simple-product-page-challenge">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Contact](#contact)

<!-- OVERVIEW -->

## Overview

![Thumbnail for the Shoe Product Page coding challenge](./thumbnail.jpg)

In this project, I focused on mastering the basics of HTML and CSS syntax, learning how to incorporate images into web pages, and practicing complex layout styling using flexbox and grid. I also added interactive elements like buttons to the layout, ensuring they functioned seamlessly. By debugging layout issues, optimizing responsiveness, and refining design elements, I created a polished, user-friendly web page.


### What I learned

- <b>Why my initial <code>:not(:last-child)</code> approach didn’t work</b>: I realized the problem was in how I structured my selector. I was using .container:not(:last-child) > *, which applies styles to all children only if the container itself isn't the last child — not what I intended. What I actually needed was .container > *:not(:last-child), which targets each child inside the container, excluding the last one. That subtle difference made a big impact on how the spacing behaved.
- <b>Responsive Design Debugging</b>: I learned how to use the DevTools Inspector box model visualization. This allowed me to better visualize margins, padding, borders, and content areas, so I could better adjust spacing and avoid overflow issues. I also learned to leverage Responsive Design Mode to test how my layout adapts to different screen sizes and ensure consistency across devices.
- <b>How to prevent overflow in grid layouts</b>: To stop images from breaking out of their columns, I used:
```css
img {
  max-width: 100%;
  height: auto;
  display: block;
}
```

### Useful resources 

- [Free Code Camp](https:www.freecodecamp.org) -  I could not recommend this enough. FREE, guided, project-based HTML & CSS lessons.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media queries

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Contact

- GitHub [@mlvoorhis](https://github.com/mlvoorhis)
