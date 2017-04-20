<h1 align="center">GitIntoGitHub!</h1>
<p align="center">
The very first PHP School workshop. A revolutionary new way to learn PHP </br> Bring your imagination to life in an open learning eco-system
</p>
<p align="center">
Git, simply put, is a tool to save versions of your code. This course will show you basic workflow and core features, different ways to undo changes or save multiple versions of a project, and how to collaborate with other developers. 
</p>

# Why learn Git?
Ever have a "I lost all my work and I have a deadline the next day" moment? Git is the most popular version control tool - something that developers use to save all relevant versions of their work to avoid moments like those. Git also makes it easy for developers to collaborate and share work with others!

## Table of Contents
  1. [Introduction](#introduction)
  2. [Variables](#variables)
  3. [Functions](#functions)
  4. [Objects and Data Structures](#objects-and-data-structures)
  5. [Classes](#classes)
  6. [SOLID](#solid)
  7. [Testing](#testing)
  8. [Concurrency](#concurrency)
  9. [Error Handling](#error-handling)
  10. [Formatting](#formatting)
  11. [Comments](#comments)
  12. [Translation](#translation)
  
  ## Introduction
![Humorous image of software quality estimation as a count of how many expletives
you shout when reading code](https://www.linode.com/docs/assets/git-github-workflow-1000w.png)

  Software engineering principles, from Robert C. Martin's book
[*Clean Code*](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882),
adapted for JavaScript. This is not a style guide. It's a guide to producing
[readable, reusable, and refactorable](https://github.com/ryanmcdermott/3rs-of-software-architecture) software in JavaScript.


## **Variables**
### Use meaningful and pronounceable variable names

**Bad:**
```javascript
const yyyymmdstr = moment().format('YYYY/MM/DD');
```

**Good:**
```javascript
const currentDate = moment().format('YYYY/MM/DD');
```
**[⬆ back to top](#table-of-contents)**
