---
layout: post
title: "Bon Appetit - Food Ordering App"
date: 2017-09-04
description: A food pick-up ordering app built for an icecream parlor but scalable to include multiple restaurants. Built as a midterm project at Lighthouse Labs with a team of 3.
image: /assets/images/bon_appetit/bonappetit.png
author: Dong Hu
tags:
  - Portfolio
---
As part of my midterm project at [Lighthouse Labs](https://www.lighthouselabs.ca/), I built a food pick-up ordering app resembling UberEats for a theoretical icecream parlor. The app allows a customer(user) to place an order and a restaurant to notify the user the status of their order via a dynamic order status page and text message notification.

[Demo](https://bon-appetit-food-app.herokuapp.com/)

User demo account: `username: dong` - `password: password`

Restaurant/Admin account: `username: icecream` - `password: password`

<hr />

#### Project Walkthrough

Once a user logs in they are brought to a menu that allows them to edit their order by adding ice cream items into their mini-cart

![BonAppetit1](/assets/images/bon_appetit/1.gif)

<hr />

Order confirmation page is displayed to the user once "Submit Order!" button is pressed. A subsequent twilio message is then sent to the customer's number.

![BonAppetit2](/assets/images/bon_appetit/2.gif)

<hr />

Upon ordering the user is then can navigate to their active order page. They are able to see their order's estimated time of arrival (ETA), if their order has been completed and their order's details.

![BonAppetit3](/assets/images/bon_appetit/3.gif)

<hr />

When logged in as a admin or restaurant owner they can navigate to their restaurant's active order page that allows the restaurant to update the ETA and order completion status. Once 'done' is pressed, the order is removed from the restaurant's order page and user is notified by text message.

#### Source Code

[Github](https://github.com/chaodonghu/bonappetit_food_ordering_app)

* Stack used: HTML/CSS/SASS, Bootstrap, Javascript, AJAX, Node.js, Express, PostreSQL, Twilio API
