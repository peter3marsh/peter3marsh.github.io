---
date: 2023-11-08 10:48:05
layout: post
title: "My Projects"
subtitle: "Details on some of the projects I've worked on over the years"
description: >-
  Details on some of the projects I've worked on over the years
image: >-
  https://res.cloudinary.com/dsyak6tlh/image/upload/v1699597238/AdobeStock_237619432-scaled_v1v3z2-Neural_Network_xel5vv.jpg
optimized_image: >- 
  https://res.cloudinary.com/dsyak6tlh/image/upload/v1699597238/AdobeStock_237619432-scaled_v1v3z2-Neural_Network_xel5vv.jpg
category: 
tags:
  - computer science
  - biotech
author: mranderson
paginate: true
---
<strong> Please feel free to check out my <a href="https://github.com/peter3marsh">Github account</a> for the code to these projects.

### Current AI Projects
At the moment I am currently working with one deep learning network, and one maching learning framework to perform segmentation on retinal vessels for Cedars-Sinai hospital (under FullRes-UNet and RVGAN-Segmentation in Github). These two each provide somewhat different approaches to the segmentation tasks, but both are being trained on the public CHASEDB1, STARE, and DRIVE fundus image sets. The purpose of this research is to <em>hopefully</em> find a way to segment and define the junctions between vessels, as well as identify any possible signs of disease (the most prominent of which is diabetes). Both of these are written in Python.

Additionally, as a more rudimentary exercise in AI design with MATLAB, I took the opportunity in one of my classes to desgin a simulated ant farm. In this project there is a queen and many worker ants; these ants are tasked with exploring the environment until they find food, before bringing that food back to the queen. To do this, all workers emit <em>blue</em> pheromones when they are searching for food, and red pheromones when they have found food. Ants with food can follow the blue back to the queen, while ants in search of the food follow the red to find it.

### Game design project -- Super Peach Sisters
I'm a big gamer, and when I wanted to explore game design with a little more depth and practice my <abbr title="Object Oriented Programming">OOP</abbr> in C++, I decided to make a super mario bros knockoff. It's fairly easy to design levels (they're just text files with symbols essentially) and your goal in each level is just to reach the flag, as in the original Mario Bros. games. The game comes complete with all the original Mario icons and fun sound effects when you bonk a Koopa.
