# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
- This project build using flex-box 

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

-[Desktop Screenshot](../chat-app-css-illustration-master/screenshots/chat-app-css-illustration-master - Personal - Microsoft​ Edge 1_07_2022 9_52_09 AM.png)

-[Mobile Screenhots](../chat-app-css-illustration-master/screenshots/chat-app-css-illustration-master - Personal - Microsoft​ Edge 1_07_2022 9_52_27 AM.png)
-[Mobile Screenhots](../chat-app-css-illustration-master/screenshots/chat-app-css-illustration-master - Personal - Microsoft​ Edge 1_07_2022 9_52_36 AM.png)


## My process
- Started with mobile desgin first using flex box then adjusted to other screen types.
- Added the background using Befor.
- Added animation

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- Adding animation name loading-msg

To see how you can add code snippets, see below:

```html
<div class="loading-msg">
          <div class="one"></div>
          <div class="two"></div>
          <div class="three"></div>
</div>
```
```css
.loading-msg{
    display: flex;
    justify-content: right;
    border-radius: 15px 15px 3px 15px;
    -webkit-border-radius: 15px 15px 3px 15px;
    -moz-border-radius: 15px 15px 3px 15px;
    -ms-border-radius: 15px 15px 3px 15px;
    -o-border-radius: 15px 15px 3px 15px;
    background-color: var(--White);
    padding: 10px;
    margin-left: 220px;
    margin-right: 10px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
.loading-msg div{
    width: 10px;
    height: 10px;
    background-color: var(--Dark-Grayish-Violet);
    border-radius: 50%;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    -ms-border-radius: 50%;
    -o-border-radius: 50%;
    margin: 0 1px;
    animation-name: loading;
    animation-duration: 0.9s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
}

.loading-msg .two{
    animation-delay: 0.3s;
}

.load-msg .three{
    animation-delay: 0.6s;
}

@keyframes loading {
    from{
        opacity: 1;
    }
    to{
        opacity: 0.2;
}
}
```

### Continued development

- building more challenging projects.


## Author

- Frontend Mentor - [@Zinah-Zwayen](https://www.frontendmentor.io/profile/Zinah-Zwayen)




