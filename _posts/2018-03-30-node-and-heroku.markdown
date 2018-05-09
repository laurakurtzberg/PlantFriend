---
layout: post
title:  "Researching How to Set Up a Node.js app on Heroku"
date:   2018-03-01 11:45:26 -0500
author: Laura J Kurtzberg
categories: blogpost
---

What is Heroku?
--------------
One of my first questions when I was looking for a way to share my Node.js prototype was what exactly *is* Heroku? According to their
own website, [Heroku](https://www.heroku.com/what) "is a cloud platform that lets companies build, deliver, monitor and scale apps ... the fastest way to go from idea to URL, bypassing all those infrastructure headaches".

![heroku plus node]({{ "/img/nodeplusheroku.png" | absolute_url }})  

Basically, Heroku is a way to deploy a web app at a temporary web address, and in my case, an easy way to share my Node.js prototype.
By installing node and npm, as well as the heroku CLI, I was able to update a git repository with my code and then push to a git remote
called 'heroku'. To get into specifics, I followed the steps in [this easy tutorial](https://devcenter.heroku.com/articles/getting-started-with-nodejs). I won't go into too much detail because I think the
offical heroku tutorial, and the rest of the heroku documentation, does a great job walking someone through it.

![Creating an app using the heroku CLI]({{ "/img/heroku.png" | absolute_url }})  

I will say that after I follwed the steps, all I had to do was go to the link that heroku had printed in the terminal
and see my app running live. This functionality is all included with the free acount.
