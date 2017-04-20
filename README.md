<h1 align="center">Git-[Into]-GitHub!</h1>

<p align="center">
<a href="https://travis-ci.org/php-school/learn-you-php">
    <img src="https://img.shields.io/travis/php-school/learn-you-php/master.svg?style=flat-square&label=Linux">
</a>
<a href="https://ci.appveyor.com/project/AydinHassan/learn-you-php">
    <img src="https://img.shields.io/appveyor/ci/AydinHassan/learn-you-php/master.svg?style=flat-square&label=Windows">
</a>
<a href="https://codecov.io/github/php-school/learn-you-php">
    <img src="https://img.shields.io/codecov/c/github/php-school/learn-you-php.svg?style=flat-square">
</a>
<a href="https://scrutinizer-ci.com/g/php-school/learn-you-php/">
    <img src="https://img.shields.io/scrutinizer/g/php-school/learn-you-php.svg?style=flat-square">
</a>
<a href="https://phpschool-team.slack.com/messages">
    <img src="https://phpschool.herokuapp.com/badge.svg">
</a>
</p>

<p align="center">
Git, simply put, is a tool to save versions of your code.Git is the most popular version control tool - something that developers use to save all relevant versions of their work to avoid moments like those. Git also makes it easy for developers to collaborate and share work with others!
</p>
<p align="center">
<img width="700" alt="GitIntoGitHub!" src="https://www.linode.com/docs/assets/git-github-workflow-1000w.png">
</p>
Git is a software that allows you to keep track of changes made to a project over time. Git works by recording the changes you make to a project, storing those changes, then allowing you to reference them as needed.

## Table of Contents
- [Tutorials](#tutorials)
    - [What is Git and GitHub?](#what-is-git-and-github)
    - [Why use something like Git?](#why-use-something-like-git)
    - [Git Repeatedly Use Word](#git-repeatedly-use-word )
    - [Design Patterns](#design-patterns)
    - [Refactoring](#refactoring)
    - [Architecture](#architecture)
    - [Miscellaneous](#miscellaneous)
    - [Videos](#videos)
- [Git Facing Problems](#git-facing-problems)
    - [OOP Fundamentals](#oop-fundamentals)
    - [OOP Advanced](#oop-advanced)
    - [Object Oriented Design](#object-oriented-design)
- [Courses](#courses)
- [Books](#books)
- [Some Questions](#some-questions)

  1. [Introduction](#introduction)
  2. [Variables](#variables)
  3. [Functions](#functions)
  
  ## **What is Git and GitHub?**
  Thank famed software developer <b>Linus Torvalds</b> for Git, the software that runs at the heart of GitHub. (And while you’re at it, go ahead thank him for the Linux operating system, too.) Git is version control software, which means it manages changes to a project without overwriting any part of that project. And it’s not going away anytime soon, particularly since Torvalds and his fellow kernel developers employ Git to help develop the core kernel for Linux.
  Git and GitHub are two of the coolest technologies around for developers. Git, despite its complexity and rather terse beginnings, is the version control tool of choice for everyone from web designers to kernel developers. And GitHub is the social code-hosting platform used more than any other. On GitHub, you’ll find everything from playful, simple experiments to the Linux kernel itself.
  GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. 
  
  ## GitHub

 Github is a graphical interface and a sort of face-on-the internet for all sorts of files (but mostly code) that you or someone from the open source community has shared.

 Github reduces redundancy in version control and helps you to keep your project folder clean and well-managed, and allows rolling back to previous versions flexibly :)

 Not just that, Github also makes it easy for several people working on a project to collaborate and make all their changes to a common repository.

 GitHub is like Wikipedia for programmers. You can edit files, see who changed what, view old versions of files, and access it from anywhere in the world – except you’re working with source code instead of encyclopedia data. Companies use it to build software and websites, while hobbyist programmers use it to find and share projects.

 It's a hosting site for source code (computer software). It let's you keep your source code safe.

 ## Git

 Version Control System ( Keep reading and this will make sense towards the end ) .

Lets say you have a project you want to work on. 

Now you have 2 primary motives.

         (a)  To write some code

          (b)  To take up the project as a team , meaning that more than one people are going to be responsible for writing the code.

So, suppose you write a "Hello World!" program and then your friend/other developer decides that it should say "Hello, I am awesome"

instead of the original "Hello World!".

Even for this little piece of code, you will have a copy in your PC and your friend will have one in his PC. 

Lets say you change the code, now at this point your friend wouldn't know the changes you have made and vice versa.

This is where the Git magic comes.  

   ## 1. Git lets you save your code online.

   ## 2. Git will allow all the developers of a project to see what changes the other one has made.

   ## 3. It allows you to discuss issues in your code with other developers.

     And a lot more...

Git is an open-source version control system.

 ## Version control systems ?

 So, Git is a “version control system,” what’s that mean? When developers are creating something (an application, for example), they are making constant changes to the code and releasing new versions, up to and after the first official (non-beta) release.

 Version control systems store the modifications in a central repository. This allows developers to easily collaborate, as they can download a new version of the software, make changes, and upload the newest revision. Every developer can see these new changes, download them, and contribute.

  **[⬆ back to top](#table-of-contents)**

  ## **Why use something like Git?** 
  <p>
  Say you and a coworker are both updating pages on the same website. You make your changes, save them, and upload them back to   the website. So far, so good. The problem comes when your coworker is working on the same page as you at the same time. One of you is about to have your work overwritten and erased.

  A version control application like Git keeps that from happening. You and your coworker can each upload your revisions to the same page, and Git will save two copies. Later, you can merge your changes together without losing any work along the way. You can even revert to an earlier version at any time, because Git keeps a “snapshot” of every change ever made.

  The problem with Git is that it’s so ancient that we have to use the command line—or Terminal if you’re a Mac user—in order to access it, typing in snippets of code like ‘90s hackers. This can be a difficult proposition for modern computer users. That’s where GitHub comes in. </p> **[⬆ back to top](#table-of-contents)**
  ## **Git Repeatedly Use Word**
  <p>
  <b>Command Line:</b> The computer program we use to input Git commands. On a Mac, it’s called Terminal. On a PC, it’s a non-native program that you download when you download Git for the first time (we’ll do that in the next section). In both cases, you type text-based commands, known as prompts, into the screen, instead of using a mouse.

  <b>Repository:</b>A directory or storage space where your projects can live. Sometimes GitHub users shorten this to “repo.” It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.

  <b>Version Control</b>: Basically, the purpose Git was designed to serve. When you have a Microsoft Word file, you either overwrite every saved file with a new save, or you save multiple versions. With Git, you don’t have to. It keeps “snapshots” of every point in time in the project’s history, so you can never lose or overwrite it.

  <b>Commit</b>: This is the command that gives Git its power. When you commit, you are taking a “snapshot” of your repository at that point in time, giving you a checkpoint to which you can reevaluate or restore your project to any previous state.

  <b>Branch</b>: How do multiple people work on a project at the same time without Git getting them confused? Usually, they “branch off” of the main project with their own versions full of changes they themselves have made. After they’re done, it’s time to “merge” that branch back with the “master,” the main directory of the project.</p> **[⬆ back to top](#table-of-contents)**


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
