---
layout: post
title: MXSLobby
description: A game server deployment application for the online racing game MX Simulator. 
image: assets/images/mxslobby.png
live-demo: https://mxslobby.com/
source-code:
dates: June 2015 - Present
---

I am the sole developer behind the project and I provide all the training content and technical support myself. The project is developed mainly with PHP, HTML, CSS, and JavaScript. Some additional languages such as Python and shell are used to execute some lower-level commands. MySQL is the database used for this project.  At the time of writing this, over 3000 unique users have registered accounts on the website.  This is a large number of people relative to the total size of the niche community.

The web application is comprised of many different parts which are each designed to accomplish different tasks.

### Some of the key things I learned from this project are:
* Permissions Management
* API Integration
* Subscription Billing
* Automated game server deployment
* MySQL
* PHP
* Python 
* Communicating with a game server via UDP packets
* Providing customer support
* Testing and refactoring


### The three main sections are:
1. The main website.
2. The game server deployment and control system.
3. The content website.

### The Main Website

The main website is the landing for all website visitors.  It was the first part of the website to be built and is used for various things.  Firstly, it is used as a hub for all important news and information.  

<img src="../../../assets/images/mxslobby/01.png" alt="" />

It is also used as a race hosting platform where users are able to easily post their own organized races for the game.  These races are integrated with the game servers which allow users to easily host races in various popular race formats.

<img src="../../../assets/images/mxslobby/02.png" alt="" />

<img src="../../../assets/images/mxslobby/03.jpg" alt="" />

The site can also poll any online game server for results in order to extract qualifying lap times and race results.

<img src="../../../assets/images/mxslobby/04.jpg" alt="" />

As mentioned above, over 3,000 unique users have registered for the website.

<img src="../../../assets/images/mxslobby/05.png" alt="" />

### The Game Server Hosting Platform

The game server hosting platform is by far the most popular component of the website.  Users are able to pay a monthly fee to deploy and control their own personal game server.  This server is automatically created once a user submits a new order.  The server is then controllable by a user through a custom control panel designed to make server management as easy as possible.  The control panel also integrates with the main website to allow users to easily host organized races in-game.

The payments are handled using PayPal in conjunction with the PayPal IPN.  This allows for secure subscription billing and automated deployment and deletion.  Users are able to view a nice one-page website outlining the features they can expect when subscribing.  That page can be viewed here: <a href="https://mxslobby.com/buy/" target="_blank">https://mxslobby.com/buy/</a>

<img src="../../../assets/images/mxslobby/06.png" alt="" />

<img src="../../../assets/images/mxslobby/07.png" alt="" />

<img src="../../../assets/images/mxslobby/08.png" alt="" />

### The Content Website

The newest addition to the website is the section used to host original content.  Content ranges from magazine-style race coverage to in-depth technical tutorials.  The content is provided by a variety of authors with different backgrounds and skills.  This section is implemented using the Wordpress CMS.

<img src="../../../assets/images/mxslobby/09.png" alt="" />

Due to the fact that this application is currently in live deployment, the source code is not viewable in a public repository.  However, I am completely willing to share and explain the source code with any potential employers upon request.