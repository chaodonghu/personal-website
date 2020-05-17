---
layout: post
title: "Chatty - LiveChat App"
date: 2017-07-04
description: A react application that allows users to have live conversations.
image: /assets/images/chatty/1.png
author: Dong Hu
tags:
  - Portfolio
---
As part of the course curriculum at [Lighthouse Labs](https://www.lighthouselabs.ca/), we dove into real time live applications and component changing by utilizing React and Websockets to implement a basic chat app that supports the real time updating of state between multiple users at a time.

<hr />

#### Project Walkthrough

Each user is able to send a chat message that is subsequently broadcasted to all connected users. Connected users are able to paste in urls ending with jpg, png, gif in a message to display the images in the chat.

When a user changes their username, all connected users are notified of the username change. Additionally once a new user is connected, the 'users online' counter will be incremented. Every user has a color associated with their username, this color stays constant even when the username changes.

![ChatyApp](/assets/images/chatty/2.gif)

<hr />

#### Source Code

[Github](https://github.com/chaodonghu/chatty_app)

* Stack used: React, Node.js, Express, Websockets
