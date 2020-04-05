---
layout: post
title: Launching with a Launcher
date: 2020-4-4
---

# Launching with a Launcher

For my new Android proect, I have decided to build a mini launcher. 

With the recent developments of working at home, I found myself constantly going back to my phone for more news feeds, more notifications and a lot more activity on the phone than I had been doing. 

I wanted to make my phone help me with my productivity. I considered the approach to uninstall all the apps that distracted me, but I felt that it was an unnecessary step because I still wanted to use the apps sometimes. So my first baby step is to make a boring launcher.

### A boring launcher

The idea is to strip the launcher of all its excess functionality and make it serve a single purpose of launching apps. My goal was to create the simplest launcher possible. To achieve this goal, I came up with the following requirements for the launcher. 

* The launcher should not have any shortcuts, notification dots, widgets, or support to add clutter to the home page.
* A swipe should show my *absolutely required* apps.
* The app icons should *look uninviting and boring*, so that I am not tempted to open the apps. I wanted to achieve this by giving a monochromatic look to the app icons.

## Result

In a short time, I was able to come up with a basic launcher that has grayscale icons, and supports a clean and tidy home-screen by not allowing anything on the surface. To give it an airy feel, I limited the number of apps on a line to 4 apps. I can still see all the apps on my phone (68 apps, too many!), but the next step will be to work on cleaning this up.

Here's how my home screen looks now.

![Home screen]({{ site.baseurl }}/images/homescreen.png)

And here's the app drawer on swiping up the screen.

![App drawer]({{ site.baseurl }}/images/appdrawer.png)



I also got rid of the app names on the launcher, since most of them have distinct icons. In case I get confused, I added settings to go back to showing the app names and showing them in their natural color as well.

## Next Goal

This is only the beginning of the project. Over the next few releases, I plan to add features that helps in increasing productivity.

Stay tuned for updates! Follow my project at [github.com/dutta14/LessLauncher](https://github.com/dutta14/LessLauncher)

