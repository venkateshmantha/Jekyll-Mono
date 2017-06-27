---
layout: page
title: Projects
permalink: /projects/
published: true
---

### [Virtual Eye](https://github.com/venkateshmantha/virtualeye) 
An Android application for the visually impaired; _Virtual Eye_ lets the user click an image through the app, analyzes and vocally describes it back to him/her.

Started as a hackathon project in Duke University last year, I built the application as a part of HackDuke's _Health&Wellness_ track to serve as an aid to the visually challenged. This excerpt _Findings from the 2015 National Health Interview Survey (NHIS) data release established that an estimated 23.7 million adult Americans (or 10% of all adult Americans) reported they either "have trouble" seeing, even when wearing glasses or contact lenses, or that they are blind or unable to see at all._ from an [article](http://www.afb.org/info/blindness-statistics/2) by the American Foundation for the Blind has further driven me into developing the app.

Virtual Eye uses image recognition and machine learning to analyze the image, retrieve the keywords and intelligently formulate the story from the image. The app then uses Android's Text-to-Speech module to vocally describe the image back to the user. Below are a few screengrabs of the app in action.![logo]({{site.baseurl}}/images/veye_0.png)
![fetching_audio]({{site.baseurl}}/images/veye_1.png)

#### What's next for Virtual Eye?

The app is currently in its Beta version and needs further testing and few design improvements to be live on PlayStore. It currently runs using Microsoft's Cognitive Api's and a rehaul of its analyzing module by writing a self-reliant analysis model to enable scale and volume is also being looked upon.

***

### [Senticon](https://github.com/venkateshmantha/senticon)
My first hackathon project _Senticon_ is a real-time Twitter Sentiment analysis tool built at MHacks in the University of Michigan, Ann Arbor. The web application which is live [here](senticon-prod.herokuapp.com) works by retreiving tweets for the typed in keyword/hashtag and performing sentiment analysis on them. Senticon uniquely visualizes the results through emoticons and not through those boring and complex dashboards. It was my first foray into NLP and was built with NodeJS and IBM Watson.

#### What's next for Senticon?

Although the interface is designed to be simple and easy to use, additional useful statistics like the volume of tweets analyzed and the frequency of highly repeated words will be added in upcoming releases.
