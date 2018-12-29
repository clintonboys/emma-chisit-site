---
layout: post
title: First forecast 
image:
  feature: sample-image-2.jpg
  credit: Cradle Mountain National Park, Tasmania, 2014
---

The Emma Chisit model had its official debut today: the [current forecast page](http://auselections.com/current-forecast/) was updated today with the first forecast model. The forecast is a little basic, as the following features of the model are still missing:

- marginal polls and demographic clustering
- automatic adjustment for high-profile candidates and independents (these are currently hardcoded into the model)
- probabilistic estimates and confidence intervals 

These features will all be added in the coming months as the Australian Federal election draws closer.

As for the actual prediction of the model, it is currently (as expected) very close to other poll aggregates on the web. Emma has the Coalition winning 89 seats, down one from its 90-seat haul in the 2013 election. The seat-by-seat forecast also reveals very few changes. 

### Things to look out for 

In the coming months as the model updates (initially I will be updating it manually, but eventually it will all be automated) there are some things I will be keeping a close eye on:

- the model's ability to detect the PUP vote. PUP leader Clive Palmer's support has fallen off dramatically, and many polls do not even include PUP as an option anymore. Until I come up with a reasonable way of handling this, I'm hardcoding an advantage to Palmer in his seat of Fairfax which awards him the seat. 
- the contest in Indi. This seat was won by an Independent in 2013 in a close contest. I'm interested to see if the model can detect changes here.
- differences from other aggregates online, and from betting markets. 


