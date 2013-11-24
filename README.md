meteorprojects
==============

Server and Client side code that I wrote using Meteor (Node.js framework)


**Chatapp**

To run this web application first install Meteor and meteorite on your machine. 
The following will install each of them via command line:


Meteor :- curl https://install.meteor.com | /bin/sh

Meteorite :- sudo -H npm install -g meteorite


Then navigate to the chatapp/ directory and type mrt in command line to run the app.

**Usage**

The application consists of a real-time message feed, complete with account login and verification via github. If a user logins to github, then his name for future messages changes from 'Anonymous' to his/her github full name.