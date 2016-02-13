---
layout: post
title: Emma Chisit: setup on AWS 
image:
  feature: sample-image-2.jpg
  credit: Cradle Mountain National Park, Tasmania, 2014
---
Today I moved Emma Chisit to an EC2 server; this way I will be able to fully automate the model. My aim is to have a fully automated model set up by the time the election draws close enough for marginal polls to start being commissioned (the inclusion of marginal polls is the real point of differentiation for the Emma Chisit model). 

The model will perform the following workflow daily:

- update its database of polls, including marginal polls
- update its poll aggregate
- if there are no marginal polls, run a simple aggregate seat-by-seat swing adjustment using preference estimates and the strong transition model
- if there are, run clustering 1000 times, adjusting swings in clusters according to marginal seat polls 
- automatically update the current forecast graphic and page