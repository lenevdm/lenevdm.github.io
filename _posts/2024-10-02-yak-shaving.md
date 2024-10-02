---
title: "Adventures in yak shaving"
layout: post
---
I'm not one of those people who started coding when they were 9 and have taken computers apart and rebuilt them into cyborgs. When I was 9 I staged elaborate ritual sacrifices of my Barbies and got bullied by the mean girls at school like any respectable tween girl. I learned about motherboards in high school, and wrote my first line of code willingly in 2017 when I was approaching 30. (Yes, it was to print hello world in JavaScript, now get off my lawn.) This is a random way to start a story, but it's to show that I am an idiot and generally don't know what I'm doing until I learn the hard way. 

Anyway, it's notoriously difficult to estimate how long tasks will take in software development. Fun toy projects you tackle on a Saturday morning included. Why is that? There are many reasons that people who are smarter than me have explained very eloquently. But let me tell you a story.

When I first started working in engineering teams, I encountered the term yak shaving. 

![A line drawing of a yak standing in a grassy meadow.](/assets/images/DALLE_yak.webp)
(Image generated with DALL.E)

Yak shaving is when you get taken on a merry goose chase of seemingly unrelated and possibly trivial tasks in the process of trying to solve a problem, or in my case, testing out Retrieval Augmented Generation (called RAG by all the cool kids) methods in a Jupyter notebook. Sounds chill right?

What was supposed to be a simple toy project that would take me a few hours to do ended up taking most of the day to not finish.

It started innocently enough when VS Code didn't display the notebook file correctly. I needed to update VS Code. But as soon as I did, it started complaining about my Python package being out of date. So I tried to use Homebrew to update it, but first I needed to update Homebrew. Cool cool cool, can do. 

But now another problem arises - Homebrew isn't updating Python. Starting to be a little less cool, but ok. Homebrew tells me my operating system is old and no longer supported, and that I shouldn't even try logging a ticket with them. Bad lady, bad! Great, I guess I can upgrade to the latest Mac OS. 

Wrong! My 2017 Macbook Air is out of disk space. (I know I'm a peasant for having a 2017 Macbook Air to code on but I'm attached to it after going through most of a BSc with it. We've seen some shit together man.) Montage of me cleaning files, backing them up to my 12 year old external hard drive, and ripping my hair out a little bit for several hours. Finally I have scraped together enough disk space to run the OS update. I start the process and my Mac informs me it'll take about an hour. 

McDonalds break. 

When I get back, my Mac is updated to... the same OS version as before, with some patches installed. Homebrew is still telling me off for having aged equipment (peasant). So after I Google a bit I come to the disgusting discovery that I am a victim of unfettered capitalism, and that Apple stops supporting older devices after a few years. I am shook. I really thought I could just update software for a time long enough for me to save up for another Mac. 

But no. The time to upgrade is now, just before my final semester starts and I need to build a big boy deep learning project. So maybe it's fortunate that I've discovered this now. 

I Google Macs, because I mean, have you seen how pretty they are. But it turns out I can't afford the ones that are powerful enough for hardcore machine learning projects. Not even close. 

Anyway, that's how I ended up ordering a "gaming" PC with some specs that truly boggle my peasant mind for roughly the price of a new Macbook Air last weekend. I can go and pick it up from the intimidating computer guys next week.

I did eventually also somehow get the notebook file to look nice in VS Code, and finished a first iteration of the RAG project, but that's a yak for another day.