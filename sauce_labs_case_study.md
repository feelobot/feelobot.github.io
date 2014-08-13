---
title: Sauce Labs Case Study of B/R
layout: post
---
## Sauce Labs Case Study of B/R 
[![Sauce Labs
Video](http://img.youtube.com/vi/vOEndYyp1cs/0.jpg)](http://www.youtube.com/watch?v=vOEndYyp1cs)

LA leading sports news site, Bleacher Report has a monthly audience of more than
16 million unique users. Beginning in December 2012, more than 50% of site
traffic originated from mobile devices.

* Previously the QA team tested their native applications manually, but without
* an automated testing process, their mobile apps had bugs after deployment.
* Unsatisfied with the process, they searched for a better solution.
* In June of 2013, they started using Appium with Sauce because they could use
* it with their existing framework and didn’t have to learn a new language or
* set of commands.

### The Challenge

Bleacher Report is a leading publisher of sports content. Turner Sports noticed
their promise, and acquired them in 2011. Now with a monthly audience of more
than 16 million unique users, they are one of the fastest growing sports media
web sites in the US. In December of 2012, they watched their mobile traffic
climb to over 50%, but their mobile testing process and coverage wasn’t quite
up to sync with this influx of new traffic.

Long-time users of Sauce, the QA team was using Selenium at the time to
automatically test their desktop and web applications. But they didn’t have an
automated tool for testing their native app. While they tested it manually
before a deploy, bugs still made it into the application. Unsatisfied with this
process, they started looking for a better solution.

> Once we realized our mobile traffic was surpassing our desktop traffic, we
> knew we needed a way to figure out how to test all the things,” said QA
> Engineer Felix Rodriguez. “We needed native application tests too.” 

### The Solution

For testing native applications, Bleacher Report’s QA team turned to Appium in
June of 2013. Appium is an open source test automation framework for native and
hybrid iOS and Android apps. When used in tandem with Sauce Labs, it allows you
to scale your native and hybrid mobile app testing across multiple device
combinations in the cloud. 

> “What I looked for in Appium was that we didn’t have to change our already
> existing code to integrate it much, and it was using commands that we were
> already familiar with. And it integrated with Sauce,” said Felix.

The Bleacher Report QA team, comprised of five engineers, is constantly updating
their applications, doing nearly 20 deploys over a three to four day period.
Fragmentation within the Android platform adds an additional layer of complexity
and requires quick iterations within the code base to fix issues. Given the need
for frequent updates, the team wanted a tool that was reliable, and they didn’t
want to reinvent the wheel when it came to mobile test automation. Further, they
wanted to employ a similar approach — test early, test often — to mobile
testing as they do with web testing, which they’ve found helps avoid problems
down the road. 

They now regularly run 12 native application tests and 7 mobile web tests, each
checking specific end points in various scenarios. Because they’re run in
parallel, the test suite only takes approximately 2 minutes. The mobile web
tests are run at 4 different times with different parameters to cover iPhone,
iPad, and in-app experiences for both. 

### Results
Running these time-saving tests and adding Appium to their tool kit has helped
put the QA team in the position of being ahead of the curve, while tempering
their company culture in the best way possible.

> “I think a lot of us can focus on the bigger picture. We can now work on fun
> internal tools, such a deployment dashboard, that lets everyone know what’s
> being deployed to what environment,” said Felix Knowing their tests are set
> up properly keeps their culture “laid back” — a key component in battling
> stress and keeping talent within the company. “Everything can run
> simultaneously. It’s exponentially faster.”
