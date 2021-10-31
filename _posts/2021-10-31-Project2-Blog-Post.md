---
layout: post
title: "Blog 4 Project 2 Reflection"
author: "Ashley Ko"
date: "10/31/2021"
---

# Project 2 Blog Post

## Summary of Project
For Project 2 my partner, Sergio Mora, and I were tasked with creating automating the creation of six reports from the [online news popularity data set](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) which predict the number of shares `shares` for each data channel (lifestyle, entertainment, business, social media, tech, and world). We used linear models and non-linear ensemble models (random forest and boosting trees) to accomplish our goal. We created a repo for our project and used Slack as a means of communication.

My blog repo: https://github.com/akoncsugit/akoncsugit.github.io
Project 2 repo: https://github.com/Smora0713/Project-2

## What would you do differently?
Honestly, I had no major issues and therefore there isn't much to change. If I had to change one thing, I would have looked at the data set and decided which predictor variables we believed to be important before subsetting the data and creating summaries. Using the full data set created for messy plots and numeric summaries. If I had started with a smaller data set to begin with I would not have had to go back and redo some of my summaries. I also kind of wish we had decided a cleaner organization structure for our repo. Sub-folders would have been nice.

## What was the most difficult part for you?
The most difficult part was working on a repo together. Sergio was a great partner but we had issues with merge conflicts. We resolved them fairly quickly, but it felt like wasted time. I thing a large part of this was do to the output files for each report and the cache not being ignored during the initial stages. We would push and pull our cache and reports which weren't exactly necessary until the end.

## What are your big take-aways from this project?
My main take away is that I want to get better at parallel computing. I feel like the run time of our project could have been better if either of us knew how to correctly apply parallel computing in our project. My second take away is that I love how easy automation works to generate multiple reports.

Less superficially, I noticed that the data does not appear to predict shares well.