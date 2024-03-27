# Recipe page

## Table of contents

- [Overview](#overview)
    - [The Challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgements)

## Overview

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

### The challenge

This challenge will help me focus on writing semantic HTML. Use appropriate elements for each piece of content.

### Screenshot

![screenshot](https://github.com/IrieBee/fem-recipe-page/blob/main/images/screenshot.jpg)

### Links

* Solution URL: https://github.com/IrieBee/fem-recipe-page
* Live Site URL: https://IrieBee.github.io/fem-recipe-page/

## My process

### Built with

* Semantic HTML5 markup
* CSS custom properties

### What I learned

* Use emmet to write html structure.
```html
    (main>header>image+h1+p^.preparationTime>ul>li*3^^.ingredients>ul>li*5^^.instructions>ol>li*6{$.}^^.nutrition>p+section>.nutritionLabel*4>p.label+p.value)+footer>p>a:link*2
```

* How to self-host fonts
```css
    @font-face {
        font-family: 'YoungSerif';
        src: url(fonts/youngserif-regular-webfont.woff2),
             url(fonts/youngserif-regular-webfont.woff);
    }

```

### Continued development

* Getting more familiar with Emmet

## Useful resources

* Abbreviations Syntax for emmet: 
https://docs.emmet.io/abbreviations/syntax/ 
    
* Self-hosting fonts: 
  https://www.youtube.com/watch?v=zK-yy6C2Nck&t=496s, 
  https://css-tricks.com/snippets/css/using-font-face-in-css/
    
## Acknowledgements

* [Odin project](https://www.theodinproject.com/)
* [Frontend Mentor](https://www.frontendmentor.io/home)