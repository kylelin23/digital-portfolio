# Creating a Digital Portfolio Part 2 – GitHub Option
Welcome! In this workshop, you will be using **GitHub Pages** to deploy your website to the internet. 

## Overview
- [1. Fork the repository](#1-fork-the-repository)
- [2. Design the home page](#2-design-the-home-page)
- [3. Add the projects page](#3-add-the-projects-page)
- [4. Push your code](#4-push-your-code)
- [5. Deploy!](#5-deploy-your-website)

## 1. Fork the Repository
The first step is to fork this repository. Forking allows you to copy someone else's repository onto your machine and make your own changes to it without affecting the original. 
- Click the `Fork` button at the top right
- Name your repo to your-username.github.io so your site lives at the root url and press green `Create fork` button
- For example, because my username is kylelin23, I would name it to kylelin23.github.io

## 2. Design the Home Page
### Set Up
- Press the green `<> Code` button
- Copy the web url, we will use it later
- Open Terminal
- Run `git clone <url>` using the web url we copied
- Open VS Code
- Press `Open` and select the project folder (the name should be your-username.github.io)

### Add HTML Elements
- Add a div, heading, and paragraph element

### Add CSS Styling
- Add font size, color, and margins

## 3. Add the Projects Page
### Add Project List
- Add an unordered list and image element

### Add Navigation
- Add link element on your `index.html` linking to your projects page

## 4. Push Your Code
- `git status` to make sure you push correct files
- `git add .` to add files to staging area
- `git commit –m “commit message”` to commit
- `git push` to push changes to remote repository

## 5. Deploy Your Website
Settings -> Pages -> Choose the main branch 

In the future, all you need to do is push to the repository and it will automatically deploy! 
