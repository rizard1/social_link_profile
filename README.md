## Overview

This is my first project submitted to GitHub, where I'm also learning how to use basic GitHub tools. This may not be the best README I've written, but I’ve tried my best to explain what this project is about and how I approached the solution.

### The challenge

This is a basic social links profile with multiple link buttons:

- When the user hovers over a button, a green background color appears.

### Screenshot

![preview of the page](https://github.com/rizard1/social_link_profile/blob/main/socialLinkPreview.PNG)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Google font (Interfont)
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

The first thing I learned was how to use Google Fonts with the CSS @font-face rule, applying different font weights:
```css
@font-face {
    font-family: "interfont";
    src: url("./assets/fonts/static/Inter-Regular.ttf") format("truetype");
}
```
I didn’t remember the exact @font-face syntax, so I referred to the MDN documentation.

I didn’t use grid or flexbox for layout—just basic block elements and an unordered list for the buttons, following the color instructions provided.

When users hover over a button, there's a 0.5s delay animation where the background color transitions from its default to green. I used the transition property for this effect:

```css
li a {
  transition: background-color 0.5s 200ms, color 0.5s 200ms;
}
```

For the image size, I used the scale() function to resize it to half of its original size.

### Continued development

There's still a lot to learn in HTML and CSS, especially how to use grid and flexbox for layout.

### Useful resources

- mdn (@font-face) - https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face

## Author

- Frontend Mentor - [@rizard1](https://www.frontendmentor.io/profile/rizard1)
- bluesky - [@rizard1.bsky.social](https://bsky.app/profile/rizard1.bsky.social)
