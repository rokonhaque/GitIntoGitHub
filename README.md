<h1 align="center">Git-[Into]-GitHub!</h1>

<p align="center">
<a href="https://www.linkedin.com/in/beingrokon">
    <img src="https://cdn3.iconfinder.com/data/icons/free-social-icons/67/linkedin_square_color-128.png">
</a>
<a href="https://twitter.com/BeingDevApp">
    <img src="https://cdn2.iconfinder.com/data/icons/social-media-2102/100/social_media_network-07-128.png">
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
    - [GitHub is not just for developers](#github-is-not-just-for-developers)
    - [Other Version Control System](#other-version-control-system)
 
- [Git Facing Problems](#git-facing-problems)
    - [Cannot Push to Github Everything Up to Date](#cannot-push-to-github-everything-up-to-date)
    - [Push rejected fetch first problem](#push-rejected-fetch-first-problem)
    - [How do I rename a local Git branch](#how-do-i-rename-a-local-git-branch)
    - [Renaming a file using the command line](#renaming-a-file-using-the-command-line)
    - [Muster push problem must read](#muster-push-problem-must-read)
  
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
 Similarly, people who have nothing to do with the development of a project can still download the files and use them. Most Linux users should be familiar with this process.

## Terminology :

A repository is a folder inside which you are going to store every piece of your code.

Copying someones repository into your account is called forking.

The guy or organisation which owns the code that you forked.

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

## **Git-Specific Commands**

Since Git was designed with a big project like Linux in mind, there are a lot of Git commands. However, to use the basics of Git, you’ll only need to know a few terms. They all begin the same way, with the word “git.”

<b>git init:</b> Initializes a new Git repository. Until you run this command inside a repository or directory, it’s just a regular folder. Only after you input this does it accept further Git commands.

<b>git config:</b> Short for “configure,” this is most useful when you’re setting up Git for the first time.

<b>git help:</b> Forgot a command? Type this into the command line to bring up the 21 most common git commands. You can also be more specific and type “git help init” or another term to figure out how to use and configure a specific git command.

<b>git status:</b> Check the status of your repository. See which files are inside it, which changes still need to be committed, and which branch of the repository you’re currently working on.

<b>git add:</b> This does not add new files to your repository. Instead, it brings new files to Git’s attention. After you add files, they’re included in Git’s “snapshots” of the repository.

<b>git commit:</b> Git’s most important command. After you make any sort of change, you input this in order to take a “snapshot” of the repository. Usually it goes git commit -m “Message here.” The -m indicates that the following section of the command should be read as a message.

<b>git branch:</b> Working with multiple collaborators and want to make changes on your own? This command will let you build a new branch, or timeline of commits, of changes and file additions that are completely your own. Your title goes after the command. If you wanted a new branch called “cats,” you’d type git branch cats.

<b>git checkout:</b> Literally allows you to “check out” a repository that you are not currently inside. This is a navigational command that lets you move to the repository you want to check. You can use this command as git checkout master to look at the master branch, or git checkout cats to look at another branch.

<b>git merge:</b> When you’re done working on a branch, you can merge your changes back to the master branch, which is visible to all collaborators. git merge cats would take all the changes you made to the “cats” branch and add them to the master.

<b>git push:</b> If you’re working on your local computer, and want your commits to be visible online on GitHub as well, you “push” the changes up to GitHub with this command.

<b>git pull:</b> If you’re working on your local computer and want the most up-to-date version of your repository to work with, you “pull” the changes down from GitHub with this command.
**[⬆ back to top](#table-of-contents)**

## **GitHub is not just for developers**

All this talk about how GitHub is ideal for programmers may have you believing that they are the only ones who will find it useful. Although it’s a lot less common, GitHub can actually be used for any types of files – so if you have a team that is constantly making changes to a word document, you can actually use GitHub as your version control system. This practice isn’t common as there are better alternatives, but keep it in mind.**[⬆ back to top](#table-of-contents)**

## **Other Version Control System**
There isn’t only Git for this, here is a list of other Version Control System.

     CVS
     Subversion
     Bazaar
     Bitkeeper

Learn

If you want to learn GitHub, I would recommend you to first learn on Git (at least understand what the usual work flow is) and then try and host some small repository on GitHub.

Once you're done with that much, you should go for advance things like forking, branching, merging, pull requests etc...

Remember, there's a lot to learn in Git & GitHub. It will take some time, so be patient.
**[⬆ back to top](#table-of-contents)**

## **Cannot Push to Github Everything Up to Date**
**[⬆ back to top](#table-of-contents)**


## **Push rejected fetch first problem**
Probably somebody else has pushed to master already, and your commit is behind. Therefore you have to fetch, merge the changeset, and then you'll be able to push again.

If you don't (or even worse, if you force it by using the <b>--force</b> option), you can mess up the commit history.

EDIT: I get into more detail about the last point, since a guy here just gave the Very Bad Advice of using the <b>--force</b> option.

As git is a DVCS, ideally many other developers are working on the same project as you, using the same repository (or a fork of it). If you overwrite forcefully with your changeset, your repository will mismatch other people's, because "you rewrote history". You will make other people unhappy and the repository will suffer. Probably a kitten in the world will cry, too.

TL;DR

    If you want to solve, fetch first.
    If you want to hack, use the --force option.

You asked for the former, though. Go for 1) always, even if you will always use git by yourself, because it is a good practice.


You should use <b>git pull</b>, that´s command do a <b>git fetch</b> and next do the <b>git merge</b>.

If you use a <b>git push origin master --force</b> command, you may have problems in the future.


<h2>Try this git command</h2>

git push origin master <b>--force</b>

or short of force <b>--f</b>

git push origin master <b>--f</b>



<h2>try:</h2><br>
<b>
git fetch origin master<br>
git merge origin master<br>
</b>
After to wrote this code I received other error: (non-fast-forward)

I write this code:<br>
<b>
git fetch origin master:tmp
git rebase tmp<br>
git push origin HEAD:master<br>
git branch -D tmp<br>
</b>
And resolved my problem


pull is always the right approach but one exception could be when you are trying to convert a none-Git file system to a Github repository. There you would have to force the first commit in.<br>
<b>
git init <br>
git add README.md<br>
git add .<br>
git commit -m "first commit"<br>
git remote add origin https://github.com/userName/repoName.git<br>
git push --force origin master<br>
</b>
**[⬆ back to top](#table-of-contents)**

## **How do I rename a local Git branch**

If you want to rename a branch while pointed to any branch, do:

<b>git branch -m [oldname] [newname]</b>

If you want to rename the current branch, you can do:

<b>git branch -m [newname]</b>

A way to remember this, is <b>-m</b> is for "move" (or <b>mv</b>), which is how you rename files.

<h2>1. Rename your local branch</h2>

If you are on the branch you want to rename:

<b>git branch -m new-name</b>

If you are on a different branch:

<b>git branch -m old-name new-name</b>

<h2>2. Delete the old-name remote branch and push the new-name local branch</h2>

<b>git push origin :old-name new-name</b>

<h2>3. Reset the upstream branch for the new-name local branch</h2>

<b>git push origin -u new-name</b>
**[⬆ back to top](#table-of-contents)**

## **Renaming a file using the command line**

<p>Main Command : <b>git mv application.py newApplication.py</b><br>
<b>git status</b><br>
 On branch buildServer<br>
 Changes to be committed:
   (use "git reset HEAD [file]..." to unstage)<br>
  renamed:    application.py -> newApplication.py </p> <br>

Many files can be renamed directly on GitHub, but some files, such as images, require that you rename them from the command line.

This procedure assumes you've already:

    Created a repository on GitHub, or have an existing repository owned by someone else you'd like to contribute to
    Cloned the repository locally on your computer

    Open Git Bash.

    Change the current working directory to your local repository.

    Rename the file, specifying the old file name and the new name you'd like to give the file. This will stage your change for commit.

   <b> git mv old_filename new_filename</b>

    Use git status to check the old and new file names.

    <b>git status
    # On branch your-branch
    # Changes to be committed:
    #   (use "git reset HEAD ..." to unstage)
    #
    #     renamed: old_filename -> new_filename
    #
    </b>
    Commit the file that you've staged in your local repository.

    <b>git commit -m "Rename file"</b>
    # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.

    Push the changes in your local repository to GitHub.

    <b>git push origin your-branch</b>
    # Pushes the changes in your local repository up to the remote repository you specified as the origin
**[⬆ back to top](#table-of-contents)**
## **Muster push problem must read**
 Github এ master দিয়ে push করার সময় একটু সতর্ক থাকতে হবে, কারন আমার সাথে যেটা হত, ধরো master এ একবার অনেক file push করলাম তারপর আরেকদিন master এ আরও file push করলাম তো 
master এ নতুন file push করার ফলে master এর আগের সব file delete হয়ে গেছে । এটা আমার সাথে অনেকবার হয়েছে । পরে তো মাথায় হাত । তাই জতদিন পর্যন্ত এর একটা সমাধান না পাই ততদিন পর্যন্ত master এ
নতুন file upload করার আগে আগের master এর file গুলা clone বা download করে রাখবো । টা না হলে আবার মাথায় হাত দিতে হবে ।
**[⬆ back to top](#table-of-contents)**
