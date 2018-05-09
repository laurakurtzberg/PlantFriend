---
layout: post
title:  "Health Calendar Component"
date:   2018-03-01 11:45:26 -0500
author: Laura J Kurtzberg
categories: blogpost
---
Health Calendar Component
=========================

The health calendar allows the user to see if the plants needs are meet each week. Each leaf is represents one of the sensor's measurements on one day of the week. A line denotes the weekly average to provide a comparison. This visualization is somewhere between a heat map matrix and encoded pictograms. When the user clicks on the information icon, a legend for this visualization appears, and then the user can exit out and continue exploring the web app.   

![Health Calendar on Mobile]({{ "/img/mobilephone.png" | absolute_url }})


This component makes use of tabletop.js to pull the data collected from the sensors that is stored in google spreadsheets (this connection to google spreadsheets was accomplished using the IFTTT functionality that is already set up for Seeed physical computing applications. After pulling the data from the spreadsheets using tabletop.js, the health calendar updates the svg gradients of each svg leaf, raising or lowering the level of darker green in proportion to the average sensor values. The lines, on the other hand, are adjusted using positioning of svg paths through a transform animation.
