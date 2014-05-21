thismatters-site
================

This Matters Project - Infantile Spasm - Why this matters - http://thismatters.info - Empowering the IS Community and raising awareness to find a cure. 

Preface
-----

**Repository Guidelines**

Do not, by any means, force push to master, In an event that it may seem necessary, please plovide additional information to Daniel Chang.

Fork the repository and create a pull request to submit any change that you want to add to the project.

Setup
-----

**Pre clone**

This project was setup usign Yeoman (1.0?)  http://yeoman.io/index.html, the latest version use 

* Yo

* Grunt

* Bower 

Using the following generator with

* Twitter Bootstrap 

* Mobile Generator

Yeoman use npm https://www.npmjs.org/ for Node.js http://nodejs.org/
The site was created with Node v0.10.28 We recomend to install NVM https://github.com/creationix/nvm to manage your Node JS instalations 

Follow the instructions in the website to install Yeoman, and all the tools that are pre-requisites to run the site.

**Getting Started**

1. Clone the repo
2. Run `npm install`. 
3. Run `bower install`.

Server
------
The developer server is configured to run on 'localhost:9000', you can start it with 
`grunt serve`


Deploy
------
You can generate a build with the comand
`grunt --force`