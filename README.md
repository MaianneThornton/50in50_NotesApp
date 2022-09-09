# 50 Projects in 50 Days - Notes App

This is a code along project in the [50 Projects In 50 Days - HTML, CSS & JavaScript Udemy Course](https://www.udemy.com/course/50-projects-50-days/). Sharpen your skills by building 50 quick, unique & fun mini projects.

## Table of contents 😌

- [Overview](#overview)
  - [The project](#the-project)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Code snippets](#im-really-proud-of-these-code-snippets%EF%B8%8F)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview👋🏾

Welcome to the 33<sup>rd</sup> mini-project of the course!

### The project😥

In this project users will be able to:

- Build a notes app that allows users to save the notes to local storage via the local storage API.

### Screenshot🌇

![](./screenshot.gif)

### Links👩🏾‍💻

- Live Site URL: (https://peppy-pixie-8b6722.netlify.app/)

## My process💭

This is a CRUD project that I started by marking out initial structure, classes, and id's in HTML. Next I finalized the UI by styling the CSS. I styled the background, add note button, notes div, icons and textarea. I then added functionality by way of JavaScript to add a new note and save the text to local storage. This ensures that the notes will be accessible until users delete them. I also added functionality to allow users to remove notes from local storage.

### Built with👷🏾‍♀️

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript

### What I learned👩🏾‍🏫

I learned the how to save, edit, and remove data from local storage. I will be applying this to future projects where needed.

I also learned how to use the marked library to access markdown language to add formatting elements to plaintext text documents.

I learned how to use JSON methods to parse data (JSON.parse), and convert text to strings (JSON.stringify).

### Continued development🔮

In the future I plan on continuing to practice creating HTML elements in JavaScript.

I also plan on continuing to practice using event listeners to make my pages more functional.

I also plan on continuing to learn the best ways to phrase git commits, so that future viewers can fully understand the changes that have occurred.

### I'm really proud of these code snippets✂️

```js
function updateLS() {
    const notesText = document.querySelectorAll('textarea')

    const notes = []

    notesText.forEach(note => notes.push(note.value))

    // console.log(notes);
    localStorage.setItem('notes', JSON.stringify(notes))
}
```

### Useful resources📖

- [Resource](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/) - This is an amazing article which helped me write better commit messages. I'd recommend it to anyone still learning this concept.

## Author🔎

- Website - [Portfolio Site](https://maiannethornton.netlify.app/)
- Frontend Mentor - [@MaianneThornton](https://www.frontendmentor.io/profile/MaianneThornton)
- GitHub - [@MaianneThornton](GitHub.com/MaianneThornton)
- Twitter - [@MaianneThornton](https://twitter.com/MaianneThornton)
- LinkedIn - [@MaianneThornton](https://www.linkedin.com/in/maiannethornton/)

## Acknowledgments🙏🏾

Special Thanks go to [Brad Traversy](http://www.traversymedia.com/) and [Florin Pop](http://www.florin-pop.com/) creating the course and making reviewing concepts fun 😊.
