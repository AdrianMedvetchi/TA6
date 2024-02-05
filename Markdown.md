# Introduction
## What is GIT?
***Git*** is a distributed version control system (DVCS) used for tracking changes in source code during software development. It was created by Linus Torvalds in 2005 and has become one of the most widely used version control systems in the world. Here are some key aspects of Git:
1. **Version Control System (VCS)**: Git helps developers manage and track changes to their source code over time. It allows multiple developers to collaborate on a project simultaneously and provides a history of changes made to the codebase.
2. **Distributed**: Git is a distributed version control system, meaning that each developer has a complete copy of the entire code repository on their local machine. This allows them to work independently and offline.
3. **Branching and Merging**: One of Git's powerful features is its support for branching and merging. Developers can create branches to work on new features or bug fixes without affecting the main codebase. Once their work is complete, they can merge their changes back into the main branch.
4. **History and Commit Tracking**: Git maintains a detailed history of all changes made to the codebase. Each set of changes is called a "commit," and developers can add comments to describe the changes made in each commit. This makes it easy to understand the evolution of the project over time.
## What is GitHUB?
***GitHub*** is a web-based platform and service that provides hosting for software development projects using Git for version control. It allows users to host Git repositories online. Developers can push their local Git repositories to GitHub, making it easy to collaborate with others and maintain a centralized and accessible copy of the codebase.

# Structure of Markdown instructions

## Text Style

If you want the text style to be italics, you need to write it between [*], for example: *text style in italics* or in alternative _like this_

If you want the text to be bold, write it between [**], for example: **text style in italics** or in alternative __like this__

To create a conflict i will paraphrase this line: There can be a lot of alternatives for the text style by combining [_] with [*] and it can be written in bold-italics style, for example: *__text is bold-italics__* or _**this way**_ or ___this way___ or ***like this***

## Lists

To make a dot-list do:

* element 1
* element 2

or 
+ element 3

To make a numbered list do:
1. element 1
2. element 2
3. element 3

## Images
To add an image do next:

![beautiful image](<beautiful image.jpg>)
## Sites

I will attache the link to github:
https://github.com/AdrianMedvetchi/geekbrains_lessons/commits/81782fa338942d59194bfe69c5d14ba55e1aa3f7/hellowworld.md

## Quotes

![Lama Quote][def]

## Finals
### Git instructions:
* Git init - to initiate the work
* Git status - to see the status of the work
* Git add - to add the modifications done
* Git commit -m "message" - to save the work with a message
* Git log - to see the history of the work
* Git branch - to see the branches
* Git branch _branch name_ - to create a branch
* Git checkout _branch name_ - to enter a branch
* Git branch -d _branch name_ - to delete a branch
* Git diff - to see the difference between curent file and the commited one
### Github instructions:
* Git remote add origin _repository url_ - is used in Git to set up a connection to a remote repository
* Git branch -M master - is used to rename the current branch in Git, -M: This option indicates that you want to move or rename an existing branch
* Git push -u origin master - pushes the local changes from the "master" branch to the remote repository named "origin" and sets up tracking for future push and pull operations
* Git pull - transfer the changes commited on github
### Comments:
[def]: <Dalai Lama quote.jpg>

Something went wrong, because the lists and images content was deleted when merged a branch. To fix it i will try to checkout commit the version where this error happened. Nothing changed, the lists and image sections remain null -> next I will create a branch for lists and a branch for images and will add the content again.
