---
layout: post
title:      "CLI Data Gem"
date:       2017-10-31 22:48:06 +0000
permalink:  cli_data_gem
---


This is about the first portfolio project that I have done for FlatIron School. It is a simple enough piece of software meant to bring together and demonstrate competency of several skills using Ruby. The project has been very beneficial for me to face several challenges that I had not had the opportunity to face during the standard curriculum.

The Ruby skills used were almost all things that I am extremely comfortable with. The skill that was my primary difficulty was web scraping. I was never really partial to guess and check so parsing the html in shell was not something that I wanted to spend a ton of time doing. Finally thrown into the deep end, swimming was a bit easier than I had previous thought.

My project was scraping a inspirational quote website that had a trait unfortunate for me. I intended to scrape their different types of  quote, and maintain their theme in the differentiation. Unfortunately each one was presented inside containers that were entirely identical except for their contents. Because of this I decided to scrape all of them into a single pile and sort it later. This solution would end up giving me one benefit and one difficulty later.

By scraping all of the content at once and allowing the program to sort it at the user's desire, the scraping method could be called once. Further, it could scrape as it was loading, which ended up making it much faster to respond to the user later on. I was pleased with the accidental benefit.

The problem I ran into was that this method of pulling the data didn't make great use of object orientation. All of the methods ended up being class methods, not what I was hoping for. At the time of project submission I couldn't think of a way to refactor the code to fit an object model better without needlessly reducing the efficiency of the program.

The greatest challenge in this lab for me was (probably) entirely unrelated to the intended rubric. My greatest challenge? Windows.

I decided to do the program outside of FlatIron's "Learn" IDE. I have been otherwise satisfied with Learn pretty much living in a sort of proxy quarantine on a virtual drive on my machine. I didn't really feel like that would be conducive to this particular project, so I decided to try it using my own tools. Truly, convenience had become my luxurious sin. 

As a notorious Windows cool-aid drinker, I really enjoy Visual Studio. I wanted to do this project in VS Code. I had not done a single thing in that editor yet. I'm also a notorious glutton for punishment. Getting Ruby to work in PowerShell and connecting to Github were probably the most lengthy parts of this project. 

At this time, the remaining part of this project is one more task I have not done before, screen capture. For sake of convenience I may try VLC's video capture, however, in my brief research on the topic I have learned that Windows has a relatively unknown option for it in Windows 10. But then, maybe I should do favor to the argument that I'm not a total fanboy.

https://github.com/bhosley/hosley-cli-app
