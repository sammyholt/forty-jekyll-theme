---
layout: post
title: Express Tasks
description: This is a simple task management application developed using Express and Node.
image: assets/images/expresstasks.png
live-demo: https://expresstasks.sammyholt.com/
source-code: https://github.com/sammyholt/expresstasks
dates: July 2018
---

This small project allows users to create an account and manage their tasks. Users can create, edit, and delete tasks as well as sort the tasks using drag and drop.

### How to Run
1. Install required dependencies with `npm install`
2. Ensure MongoDB is installed on your local machine
3. Run the project with `npm start`
4. Visit `localhost:5000` in your web browser

### Some of the key things I learned from this project are:
- Creating an application using Node and Express
- Using MongoDB to store and load data
- User authentication using passport and bcrypt
- Using environment variables to store sensitive configuration settings
- Live deployment to a cloud service


### Features
- Add/Edit/Delete Tasks
- Tasks unique to each user account
- Only add and edit tasks for user's own account
- Drag and drop tasks to sort them 
- Sorting saves to database immediately

