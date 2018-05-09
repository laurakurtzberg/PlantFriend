---
layout: post
title:  "Moment Flowers - combining notifications and data viz"
date:   2018-03-01 11:45:26 -0500
author: Laura J Kurtzberg
categories: blogpost
---

Moment Flower Component
======================

The moment flower is a way to merge notifications and visualization in a new and artistic way. Combining notifications and data visualization for at-a-glance information in both text and visual form was an idea that came from user feedback. Comments from users emphasized their enthusiasm for the friendship and personalization component, while also expressing interest in getting a quick verification of the status of their plant.

![Moment Flower]({{ "/img/zuzumomentflower.png" | absolute_url }})

Each moment flower corresponds to one plant, and is a visualization made up of four petals that represent the four environmental variables affecting that Plant Friend. The more saturated the color, the better the plant is in that category. Recommendations appear on the status flower to help the user decide what to do in that moment. If everything is fine with the plant and there are no current notifications, the colors will be saturated and the message will simply alert the user that their plant is healthy, reassuring them that at the moment, they don't need to make any changes in the plants environment.


The moment flower is a feature that is still in it's idea stages. To create an actual demo that draws from the data would be similar to the process
used for the other components of the web app - getting data either real time from the Wio Link API or from the past as it is stored in a Google spreadsheet,
and then mapping the incoming values to a scale of recommended values for environmental variables. This scale can then be mapped to a color scale for each
petal of the visualization, where a more saturated value for each petal corresponds to a healthier environmental variable for the plant.

![Many Plant Friends]({{ "/img/plantfamily.png" | absolute_url }})
