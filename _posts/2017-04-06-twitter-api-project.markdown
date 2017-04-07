---
layout: post
title:  "Twitter API Project"
date:   2017-04-06 -0700
categories: blog update
---

Hi all,

So, I was scrolling through my twitter feed earlier today and I say an interesting article tweeted by TechCrunch. My first reaction was to DM it to myself for "later reading." I always do this. I mean ALWAYS. My DM is filled with tweets about things that I find interesting, but don't have the time to read at the moment. After 15-20 minutes of scrolling through my feed and DM'ing myself articles, I've lost track of what was what and I never get around to reading any of the articles, because of the unorganized mess that is my DMs.

This got me to start thinking on making a Twitter Bot that would track tweets from my favorites twitter users and store tweets that link to articles into a SQL or MongoDB server. In this database I would store informations about the user as well, for example I would store the accounts username, date of tweet, link to article, etc. Then I could make a front end that would grab that info and neatly organize it into certain categories (I'm not sure which yet, maybe like by user and date?). This way, I don't have to constantly hunt down my timeline for articles that I will never read. Instead, all I have to do is go to this article haven site and read at my leisure.

That's all for now.

P.S. Finally this domain 'ayahya.me' was being used by my old AWS account and in that S3 bucket I had...I'm not sure what I did back then, but I somehow managed to get S3 to log multiple healthcheck files per hour and store them into the dir 'log'. I got around to deleting that old S3 bucket today and had to delete over 400k log files...You read that right 400 Fucking THOUSAND log files...wtf. I can't believe I did something like that.... Anyways enough griping. I got the site up and running on my domain finally and I will be working on getting cloudfront and HTTPS setup next.
