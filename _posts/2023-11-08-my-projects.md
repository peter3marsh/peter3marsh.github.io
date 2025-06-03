---
date: 2025-3-08 10:48:05
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
  - AI
  - machine learning
author: mranderson
paginate: true
---
<strong> Please feel free to check out my <a href="https://github.com/peter3marsh">Github account</a> for some of the code to these projects.

### Recent AI Projects

My primary project at Cedars-Sinai involved designing and training a deep learning model for segmenting the pancreas and any possible tumors in abdominal CT scans. This model is integrated with a larger end-to-end process intended for clinical applications, wherein we are able to assess the risk of pancreatic adenocarcinoma (PDAC) for a given patient using their medical history and the data from my DL model in a subsequent machine learning model.

During my time at Cedars-Sinai hospital I also had another ongoing project using one deep learning network, and one maching learning framework to perform segmentation on retinal vessels (under FullRes-UNet and RVGAN-Segmentation in Github). These two each provide somewhat different approaches to the segmentation tasks, but both are being trained on the public CHASEDB1, STARE, and DRIVE fundus image sets. The purpose of this research is to <em>hopefully</em> find a way to segment and define the junctions between vessels, as well as identify any possible signs of disease (the most prominent of which is diabetes).

### App Design Projects

Recently I also spent time working with a startup app project intended to help homeowners track their spending on house projects/purchases. As a backend engineer, I set up a workflow using AWS services that allows app subscribers to forward their invoices to an email inbox, and use computer vision to automatically extract data from the invoice and create a receipt in the app for the user. Part of the code used for data extraction was also used to extract data from files directly uploaded to the app in a very similar manner.

In my third year as an undergraduate I worked with another team of UCLA engineers from across majors to put together a prototype for a therapeutic glove meant to aid in Parkinson's rehabilitation. I primarily worked with the microcontrollers that took in sensor data for the glove, and helped with data processing and display within the companion app that we created for the glove.

### Past AI Projects

For other final project in my senior machine learning course, I worked on computer vision model intended for classifying students as either UCLA or USC students based on pictures of them. I trained it on a self-compiled dataset of images from each of the schools' merch advertisements. This was the first work that I did with computer vision, and helped me decide to work on the capstone project with Cedars-Sinai's Biomedical Imaging Research Department.

Additionally, as a more rudimentary exercise in AI design with MATLAB, I took the opportunity in one of my classes to desgin a simulated ant farm. In this project there is a queen and many worker ants; these ants are tasked with exploring the environment until they find food, before bringing that food back to the queen. To do this, all workers emit <em>blue</em> pheromones when they are searching for food, and red pheromones when they have found food. Ants with food can follow the blue back to the queen, while ants in search of the food follow the red to find it.

### Game design project -- Super Peach Sisters
I'm a big gamer, and when I wanted to explore game design with a little more depth and practice my <abbr title="Object Oriented Programming">OOP</abbr> in C++, I decided to make a super mario bros knockoff. It's fairly easy to design levels (they're just text files with symbols essentially) and your goal in each level is just to reach the flag, as in the original Mario Bros. games. The game comes complete with all the original Mario icons and fun sound effects when you bonk a Koopa.
