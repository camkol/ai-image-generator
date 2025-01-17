# AI Image Generator

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- Run search for ai generated image

### Screenshot

![](./screen.jpg)

### Links

- Live Site URL: [Live](https://aiimagegenerator171.netlify.app/)

## My process

- The `App` component renders the `ImageGenerator` component, which is responsible for generating AI-based images from user input.
- In `ImageGenerator`, a user types a prompt into an input field, and the input is captured using a `ref` (`inputRef`).
- When the "Generate" button is clicked, the `imageGenerator` function sends a POST request to the OpenAI API with the prompt, using an API key stored in an environment variable (`REACT_APP_AI_GEN_API_KEY`).
- While the request is being processed, a loading indicator (`loading`) is displayed, and once the response is received, the URL of the generated image is extracted and displayed in an `<img>` element.
- If no input is provided, the function exits early without making the API call, and a default image is shown until a valid image URL is generated.
- The design includes a CSS-based loading bar and text that appear during the API request, enhancing the user experience.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Mobile-Responsive Design
- JavaScript - Scripting language
- [React](https://reactjs.org/) - JS library

### What I learned

still thinking....

### Continued development

I hope to integrate this into my workout app project.

## Author

- Website - [Cameron Howze](https://camkol.github.io/)
- Frontend Mentor - [@camkol](https://www.frontendmentor.io/profile/camkol)
- GitHub- [@camkol](https://github.com/camkol)
- LinkedIn - [@cameron-howze](https://www.linkedin.com/in/cameron-howze-28a646109/)
- E-Mail - [cameronhowze4@outlook.com](mailto:cameronhowze4@outlook.com)
