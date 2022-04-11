# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Your challenge is to build out this profile card component and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.
Want some support on the challenge? [Join our Slack community](https://www.frontendmentor.io/slack) and ask questions in the **#help** channel.


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned

I learned how to position two images with pseudo elements before and after. 




```css
.wrapper-content::after,
.wrapper-content::before {
    content: '';
    position: fixed;
    width: 100vw;
    height: 100vh;
}

.wrapper-content::before {
    transform: translate(-50%, -50%);
    background: url('/images/bg-pattern-top.svg') bottom right no-repeat;
}

.wrapper-content::after {
    transform: translate(50%, 50%);
    background: url('/images/bg-pattern-bottom.svg') top left no-repeat;
}
```

## Author
- Frontend Mentor - [@JorgeIturrieta](https://www.frontendmentor.io/profile/JorgeIturrieta/solutions)


