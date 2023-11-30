# Exercise 1: Using GitHub and Git

This document describes the process I followed to create a new repository on GitHub and clone it to my local machine using the Git command line.

## Creating a GitHub Account

First, I visited GitHub and signed up for a new account.

## Creating a New Repository

Once I had my account, I created a new repository by clicking on the '+' icon in the top right corner of my GitHub homepage and selecting 'New repository'. I gave my repository a meaningful name related to my project.

## Cloning the Repository to My Local Machine

After creating the repository, I cloned the repository to my local machine. To do this, I copied the URL of the repository from GitHub and pasted it into the following command in my terminal:

```bash
git clone https://github.com/Joe-cmd-doc/GithubActivity.git
```
## Creating a Markdown File

Next, in the directory of my local repository, I created a new file called `E1Github.md` using the following command:

```bash
touch E1Github.md
```
## Documenting the Process
I opened E1Github.md in my text editor and documented the steps I followed, especially the Git commands I used. I formatted the Git commands as code in Markdown by wrapping them in backticks (`).

## Committing and Pushing Changes
Finally, I committed and pushed my changes to GitHub with the following commands:

```bash
git add .
git commit -m "Documented the process in E1Github.md"
git push
```
## Submitting the Repository URL
After pushing my changes, I copied the URL of my repository from the address bar of my browser and submitted it to my professor. I made sure that the repository was public or that my professor had read access to it.
