# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/sociallinksprofile-challenge-a4eq4bAjaE)

- Live Site URL: [Add live site URL here](https://social-links-profile.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design with media queries
- [Google Fonts](https://fonts.googleapis.com/) - Inter font


### What I learned

- **Responsive Design:** Implemented a mobile-first approach using CSS media queries.
- **CSS Flexbox:** Utilized flexbox for layout and alignment within the profile card.
- **Styling Techniques:** Applied custom styles, including rounded corners and background colors.
- **Media Queries:** Used media queries for responsive adjustments on smaller screens.
- **HTML Structure:** Created a structured HTML layout for a profile card with social links.
- **Google Fonts:** Integrated the Inter font from Google Fonts to enhance typography.

To see how you can add code snippets, see below:

```html
<div class="navlink">
  <div class="button">
      <a href="#">GitHub</a>
  </div>

  <div class="button">
      <a href="#">Frontend Mentor</a>
  </div>

  <div class="button">
      <a href="#">LinkedIn</a>
  </div>

  <div class="button">
      <a href="#">Twitter</a>
  </div>

  <div class="button">
      <a href="#">Instagram</a>
  </div>
</div>
```
```css
.navlink {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.button {
    background-color:  hsl(0, 0%, 20%);
    padding: 10px 15px;
    border-radius: 5px;
    margin-bottom: 15px;
    width: 250px;
    text-align: center;
}

.button a {
    text-decoration: none;
    color: hsl(0, 0%, 100%);
    font-weight: 500;
    font-size: 15px;
    display: block;
    transition: color 0.3s;
}

.button:hover {
    background-color: hsl(75, 94%, 57%);
}

.button:hover a {
    color: hsl(0, 0%, 8%);
}

```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


## Author

- Frontend Mentor - [@MvPorcalla](https://www.frontendmentor.io/profile/MvPorcalla)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

