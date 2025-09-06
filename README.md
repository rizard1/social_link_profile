## Overview

This is a first project where i submit to github also learning how to use basic github tools. This is not the best README that i write, but try my best to explain what this project is about and how i approach the solution.

### The challenge

This is just a basic social links profile with multiple link buttons:

- When the user hover over button, the green background color appear.

### Screenshot

![](.socialLinkPreview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Google font (Interfont)
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

The first thing i learn is how to use google font with css font rule @font-face with different kind of font weight apply on css:
```css
@font-face {
    font-family: "interfont";
    src: url("./assets/fonts/static/Inter-Regular.ttf") format("truetype");
}
```
I really don't remember what is @font-face syntax so i read from mdn website. 

Not using any grid or flex to sort the layout just the basic block and unordered list for buttons, using all the colors according to the instruction. 

When the users hover the cursor over the button, it will be a 0.5s delay animation the way button background changes it color from normal to green where i'm using transition property:

```css
li a {
  transition: background-color 0.5s 200ms, color 0.5s 200ms;
}
```

For the image size, i'm using scale function resize half of it's original size.

### Continued development

There's so much more to learn html & CSS especially how to use grid and flex for layout.

### Useful resources

- mdn (@font-face) - https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face

## Author

- Frontend Mentor - [@rizard1](https://www.frontendmentor.io/profile/rizard1)
- bluesky - [@rizard1.bsky.social](https://bsky.app/profile/rizard1.bsky.social)