# JS Major Project - I have a say

This is a a comment section using pure Vanilla JavaScript and HTML.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Project Description](#project-description)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

To get feedback or any message from a website visitor we need a comment box on our web page. A comment box can be created using any web technology whether it is simple HTML, CSS or even JavaScript. The three tools HTML, CSS, and JavaScript are enough to make fully functional websites.

### The challenge
- The page must always launched with one static text area at the top and an add button that allows the user to add comments.
- Every comment added will have a reply, a like, and a delete button.
- A reply button will launch a new text area below the parent comment, allowing the user to either add a reply or cancel the addition.
- A like button will keep incrementing the number of likes on the respective comment at every click.
- A delete button will delete the entire comment chain or if the user wants to delete a single comment, he can.
- Comments can be chained resembling a tree-like structure wherein every child comment will be aligned with some pixels left to the parent comment.
- Comments once added should be persisted on page re-load — this is an enhancement, I have implemented it using localStorage.


### Project Description
a. In this project, I have created a comment section. It lets users enter comments, provide replies to comments, delete a comment, like comment functionalities, and retains users' comments even after the site is closed. 
   

b. I have used HTML, CSS, and Pure Vanilla JavaScript. I did not use Bootstrap, jQuery, or any other frameworks.

c. I had implemented some of the features including;-
   - The page is always launched with one static text area at the top and an add button that allows the user to add comments.
   - Every comment added will have a reply, a like, and a delete button.
   - A reply button will launch a new text area below the parent comment, allowing the user to either add a reply or cancel the addition.
   - A like button will keep incrementing the number of likes on the respective comment at every click.
   - A delete button will delete the entire comment chain or if the user wants to delete a single comment, he can.
   - Comments can be chained resembling a tree-like structure wherein every child comment will be aligned with some pixels left to the parent comment.
   - Comments once added should be persisted on page re-load — this is an enhancement, I have implemented it using localStorage.


### Links

- Live Site URL: [Netlify](https://jatin-i-have-a-say.netlify.app/)
- Git Repo: [Github](https://github.com/JatinM95/JS-Major-Project---I-have-a-Say-)

## My process

I have created my folder which includes following files:
- index.html
- Images folder
- app.js
- styles.css

- index.html
This is the main html page, which will show the structure of our comment section website, when we load it first.

- Images folder
This folder contains all images used in our project, i.e. fevicon, logo of our website and background image of our website.

- app.js
This is the brain of our website. This file contains all javascript logic for our website, like adding comments, cancelling comments, delete, like, reply and also persistence of our comments. The logic of adding html elements as comments or buttons is also is in this file. 

- styles.css
This is the file which have all properties of how our website will look like, all the designing and styling of our website.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Vanilla Javascript

### What I learned

I have learnt dom manuplation using javascript, how to add div tag, textarea, buttons using javascript to our webpage, building comment section in tree like structure using plain javascript. Also learnt about localstorage that is used to persist comments using setItem and getItem methods. Fistly we can save it in localstorage using setItem and then to display it on our webpage we can access it threw getItem method.

### Continued development

- Add the username property to the comments(which holds some mock name of the user who is making the comment).
- The like button currently has a simple implementation. It should show 1 like, 2 likes and so on instead of 1, 2, 3 on the increment of likes.
- Allow the user to edit an existing comment.
- Add a posted-on property to each comment which displays the date and time it was last edited on/posted on.
- A way to expand and collapse the parent comment(via accordian) or any better way if possible.
- Keep the add/reply button disabled if the target textarea is empty, which will restrict the user from adding empty comments.


### Useful resources

- [W3schools](https://www.w3schools.com/js/default.asp) - This helped me for understanding javascripts complex concepts like DOM manipulation and creating functions and classes in javascript.
- [JavaScript | MDN - Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - This is an amazing source which helped me during my project. This is official documentation for javascript.
- [Section.io](https://www.section.io/engineering-education/how-to-use-localstorage-with-javascript/) - This is an amazing article which helped me in understanding how to store data and how to fetch data from localstorage.
- [Medium](https://javascript.plainenglish.io/how-to-create-a-comment-section-using-html-and-vanilla-js-aa6b6a53b9cf) - This is an amazing article which helped me in understanding how to create comment section in tree like structure.


## Author

- Author Name - Jatin Mangal
- LinkedIn - [@jatin-mangal-184972a7](https://www.linkedin.com/in/jatin-mangal-184972a7/)

