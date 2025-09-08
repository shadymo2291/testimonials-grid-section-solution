## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:https://github.com/shadymo2291/testimonials-grid-section-solution

### Built with

- Semantic HTML5 markup
- CSS custom properties
- grid
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

.one::before {
  content: "";
  width: 150px;
  height: 150px;
  background-image: url(../images/bg-pattern-quotation.svg);
  background-size: cover;
  position: absolute;
  top: 0;
  right: 50px;
  z-index: -1;
  opacity: 0;
}
@media (min-width: 769px) {
  .one {
    grid-column: span 2;
  }
  .one::before {
    opacity: 1;
  }
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
