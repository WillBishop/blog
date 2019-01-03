---
title: How I got into watchOS Development
layout: post
comments: true
---

For the first post on the blog, I wanted to go into how I got into watchOS development.

## It didn’t start with watchOS
It started in 2016. I was in year 9 in High School, and I wanted a way for my grades to get sent to my phone when they were released. At the time I had to manually check my school website every time I wanted to see if any new grades came out. This led me to create “GradeCheck” (creative name, I know). GradeCheck was written in Python, not Swift, and ran on a Raspberry Pi, not an iPhone. GradeCheck was more the start of my interest in programming. Prior to that I had some knowledge with Python, but not much. Eventually GradeCheck was ready to be released but I never did (it had some glaring security issues which I won’t go into). *But I should skip ahead a bit*

## My beginnings in Swift
Towards the end of year 9 I started developing an app to let me view my classes, grades, and homework straight from my phone, as such an app wasn’t available for my school yet. This app was developed as part of a school class called “Personal Project”, where each student creates something on their own, tailored to their interestes. Being a life long nerd, programming was my first choice. I could write a lot about that class (mostly my complaints), but I’ll either save that for another day or just never write about it, it’s a bit petty. That app never reached fruition, and is still in very slow development today. The app was also astonishingly ugly…

![Some information (like teacher and class names) have been redacted](/images/originalschoolapp.png "The original UI of my school app")

But this was enough of a start to make me love Swift and begin to want to build more things with it. 

The next 6 months of 2017, not a whole lot happened, that is until the 20th of December. 

## Why WatchKit/watchOS?

This is by far the most common question I get (and the topic of this post), and the answer may be disappointing. As for how I got into making WatchKit apps, it started on December 20th, 2017, just before Christmas. Now I knew for that year I’d be getting an Apple Watch for Christmas, it was all I wanted, it was all I asked for, and my entire family (extended too) all chipped in. Because I had an interest in developing apps for the iPhone already, and because I knew I’d soon have a device on my wrist at all times which I could program stuff for, it felt only natural to give it a shot. I also had (and probably still do) an unhealthy obsession with Reddit. I spent hours every day on Reddit, and I knew I’d want to do that on my shiny new watch. 

I researched what apps were already available to browse Reddit on my wrist, but to my surprise I didn’t really find any. Any that I did find were either incredibly basic, or simply no longer available. So that’s when I started Nano, before I even had a watch.

Tl;dr I was getting a watch for Christmas and I wanted to try out making apps for it, and it just sort of stuck.

## Nano

![Nano didn't look nearly as nice on its first day](https://i.gyazo.com/6c274d2f7ec22adf8bdb82c6f26c6510.mp4)

It took me an embarrassingly long time to figure out how to make a simple table in WatchKit, coming from UIKit it was quite the difference. People often ask *how* I learnt, but I never really have answer to that. I could say I used StackOverflow and YouTube tutorials, and that would all be true. But I don’t feel like the way I learnt will transfer over to everyone else, as teaching yourself something like Swift is quite a personal thing. 

In April of 2017, [Nano for Reddit](https://itunes.apple.com/us/app/nano-for-reddit/id1344097185?ls=1&mt=8) was released. I [posted about it on Reddit](https://www.reddit.com/r/AppleWatch/comments/8eg1nu/i_just_released_my_first_app_nano_the_wristbased/) where it quickly reached the top of the front page of the [r/AppleWatch](https://applewatch.reddit.com)

From hitting ‘New Project’ in Xcode, to hitting ‘Release’ on iTunes Connect was 5 months. Some of the most stressful months of my life (possible incurred a years worth of sleeping problems from that, but I have to wait until March to confirm). 

There were many points in that time that I just wanted to quit. I remember having a build submitted to Apple, and while I was using Nano in the car I discovered a major bug that I needed to patch. While the bug was simple enough to fix, it felt like a major punch to the stomach to have to have cancel my submission to Apple again (for the third time) over small things. The stress resulted in me missing lots of minor details in my app, which left it unpolished and not fit for launch. Throughout this, however, I had lots of testers were always happy to help, and for that I am very grateful.

The past year of my life has been incredible, and the success of my two apps has been a large factor in that. So I’d like to thank you all for your continued support, and I hope I can continue making apps and writing this blog long into the future.