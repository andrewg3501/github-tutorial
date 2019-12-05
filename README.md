# GitHub Tutorial

_by Andrew_

---
## Git vs. GitHub
git is a system for version control primarily used by programmers and others who write code
  github is a website that allows you to upload your git repositories


---
## Initial Setup
to make a github account, [go to this site here](github.com) and then click sign up with a username and password, then check your email for a confirmation
IDE stands for Integrated Development Environment and its purpose is for file trees, text editing, previewing and a command line of basic things, essentially a code editor for your repositories [which you can learn about here](github.com/hstatsep/ide50)


---
## Repository Setup
to make a new repository
1) [login to github if you haven't already at](github.com)
2) click on the new button at the top left
3) it will bring you to the repository creator, where you decide on the name of your repository and whether it is private (meaning only you and certain people can see it), or public (where everyone can see it)
4) once done you will be taken to your new repository which you can then pair with your ide to make changes

## IDE and GitHub pairing
1) [go to](ide.cs50.io) and sign in
2) once there, open the terminal and type mkdir (your repo name here). for example, in github if you made a repo called about-me, you would do mkdir about-me.
3) then cd about-me which will switch you to that repository/directory
4) use git init which will initialize the repo
5) use touch README.md which will make a file called README.md in that area
6) c9 README.md which will then open the file, add some text into the readme and then command + S on your keyboard to save
7) use git add README.md to add it, then git commit -m "whatever you changed" (example" git commit -m "added text in the readme")
8) once done do git remote add origin (github repo link here) (example: git remote add origin github.com/user123/about-me)
9) then git push -u origin master which will sync the changes
10) refresh your github repo and you should see changes!
---
## Workflow & Commands

feedback from jenny:
very nicely done, andrew! But i would suggest to try to bold and italize some words (ex: like the commands) which are very important.