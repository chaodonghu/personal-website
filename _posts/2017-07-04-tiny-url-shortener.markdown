---
layout: post
title: "Tiny URL Shortner Clone App"
date: 2017-07-04
description: A tinyURL clone web application built with Node.js and Express that allows users to shorten long URLs.
image: /assets/images/tiny_url/1.png
author: Dong Hu
tags:
  - Portfolio
---
As part of the course curriculum at [Lighthouse Labs](https://www.lighthouselabs.ca/), we dove into the backend aspects by learning how to leverage Node.js and Express to implement a basic user authentication for an app that allows users to shorten long URLs similar to bitly and tinyURL.

[Demo](https://tiny-url-app.herokuapp.com/)

<hr />

#### Project Walkthrough

The user is able to login or register, a successful or unsuccessful register/login is prompted with a corresponding flash message.

![TinyURL2](/assets/images/tiny_url/2.png)

<hr />

![TinyURL3](/assets/images/tiny_url/3.png)

<hr />

After logging in, the user is displayed a list of their shortened URLS.

![TinyURL4](/assets/images/tiny_url/4.png)

<hr />

Navigating to "Add URL", the user is then able to add URLs which will then be shortened.

![TinyURL5](/assets/images/tiny_url/5.png)

<hr />

![TinyURL6](/assets/images/tiny_url/6.png)

<hr />

Once the tinyURL has been updated, users can then navigate to the corresponding URL by clicking on it from the list of their URLs.

![TinyURL7](/assets/images/tiny_url/7.png)

#### Source Code

[Github](https://github.com/chaodonghu/tiny_url_shortener_app)

* Stack used: Node.js, Express, Bcrypt
