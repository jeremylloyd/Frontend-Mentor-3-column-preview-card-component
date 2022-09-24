# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Github](https://github.com/jeremylloyd/Frontend-Mentor-3-column-preview-card-component)
- Live Site URL: [Github Pages](https://jeremylloyd.github.io/Frontend-Mentor-3-column-preview-card-component/)

## My process

### Built with

- HTML
- CSS (BEM)

### What I learned

- CSS [BEM](https://getbem.com/introduction/) convention
  - It reduces the amount of time I spend coming up with intuitive names for elements
  - The result is some of the most maintainable CSS I've written for any project
  - Elements with a modifier need to include the base element in the class:
    - Good:
      ```
      <div class="block block--mod">...</div>
      <div class="block block--size-big block--shadow-yes">...</div>
      ```
    - Bad:
      ```
      <div class="block--mod">...</div>
      ```
- Trying to centre something? Use `flex` - it's generally less confusing than messing with margins.
