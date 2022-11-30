---
layout: essay
type: essay
title: "Checkpoint Assignment #3"
# All dates must be YYYY-MM-DD format!
date: 2022-11-29
published: true
labels:
  - Assignment
  - Checkpoint
  - Powerpoint
  - Screencast
---
<h2>Show what each page will look like. The pages do not have to be “functional” but the design should be clear. Here is an example PPT prototype.</h2>
Here is my screencast where I go over what I plan to do with each page of my website.<br>

<h2>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</h2>
For my website I plan on having my shopping cart be accessed on a separate page and all my pages (including the login and registration pages) available in the navigation bar. When a user adds a certain quantity of items to their cart (add to cart button will be implemented), then they will be able to go to their cart and view and edit their cart on that page.<br>

On the cart page, a user can look at the items they have selected and edit them (increase or decrease quantity of item or delete item altogether). I also plan on adding a checkout button on the shopping cart page so that when the user is ready to checkout, they are able to (as long as they are signed in).<br>

<h2>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</h2>
In Assignment 3 I will be implementing sessions in order to manage my shopping cart data with things such as which products are selected and the quantity of each selected product. By holding this information in a session with an array (for example: request.session[‘mugs’] = [{“mug_style”: “Avocado Mug with Matching Plate”, “quantity”: 4}]) I am able to display this information in the shopping cart for the user to view and edit. When editing this information, I plan on overwriting the old information with the updated information (similar to editing the users data on the registration page).<br>

<h2>How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</h2>
We learned in the Cookies and Sessions Lab that cookies are a good way to identify a user (in this case, based on their username). I can use cookies and if statements to identify a user and check if they have a cookie. If they do have a cookie, this means that the user has logged in already and is ready to checkout their items. If they don’t have a cookie, they have not logged in yet and need to either log in or register in order to checkout.<br>

One security concern that we also talked about in the lab is that cookies are stored on the client’s browser and therefore can be tampered with through the browser. It’s possible that this can be avoided through encrypting the data. There is also the concern that a user can leave their logged in on a public device where anyone can access their information. This could also be avoided through setting a timer on their cookie to log the user out after a certain amount of time.<br>

<h2>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary).</h2>
I plan on personalizing the UI by displaying the name or username of the person who is logged in on the home page and product pages. On the invoice page I have already implemented a thank you message as well as the users info, however, I plan on updating this information to look nicer and better fit the requirements for Assignment 3.<br>

<h2>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</h2>
I will be working on this assignment on my own, wish me luck!<br>

<h2>How are you approaching Assignment 3 differently than Assignment 2?</h2>
With Assignment 3, and now thanks to this assignment, I am better able to plan out the design and layout of what I want my website to look like before implementing any code. This will help me get a good idea of what I want and what I am trying to achieve so that I can articulate it better in my code.<br>
