---
layout: post
title:      "CLI Data Gem Portfolio Project"
date:       2020-04-18 21:34:33 +0000
permalink:  cli_data_gem_portfolio_project
---


When I was first thinking about what type of project I wanted to do, I was very unsure. There are millions of websites that I couldve gotten data from for this prject, so choosing the "right" one was definitely daunting. At first I wanted to collect data from ESPN.com and do something that involved taking scores from games, or finding when a teams most recent game was. Something along those lines, at least that was the initial idea.

Then I realized, there's no sports going on right now. That would be a big problem for finding relevant information. Then I realized it. WHY are there no sports right now? That's when I decided to do my project on providing statistics on the current COVID19 pandemic sweeping the world. I found a website that constantly has up-to-date information on the virus and also has this information for the world and individual countries. The best part of the website is that it is constantly being updated, multiple times a day even. This means that every time the gem is run, the statistics provided are as up-to date as possible.

Velocity on this project was - as expected - super fast in the beginning and the end, while the middle took some time (de-bugging and collecting the information in a clear way). Building the skeleton of the CLI, Country class, and scraper files were fairly easy and straight to the point, however getting deeper into the scraper file was more challenging. I scraped the data from the website https://www.worldometers.info/coronavirus/ and took the data from the table provided. The main issues came from the format of the table. The table had so many sorting options, that the scraping was not as simple as previous scraping labs. Once that was figured out, the scraping and country creation was complete.

The final - and probably the largest problem - came within the CLI file. I was having troubles with having menus leading to other menus and having various forms of user input to take in. Taking in the information wasn't the hard part, however. Exiting the different menus and navigating between them was the most challenging part. I eventually got it figured out and the gem works very well!

This was definitely a good project to practice all I've learned in the first few weeks of ruby programming. Class creation, scraping, iteration, object manipulation, etc. were all very fun to implement here without the "hand-holding" of constantly testing code against provided tests. This was a great project experience and it felt amazing to go from a blank workspace to a functioning gem that provideds useful information.

-Nic
