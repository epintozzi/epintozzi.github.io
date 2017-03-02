---
title: My First Open Source PR
layout: post
date: 2017-03-01 00:00:00 -07:00
---

{:.post-content}
The purpose of this project was to submit to an open source project to make positive contributions to the programmer community. I chose to contribute to a [Gitlab gem](https://github.com/epintozzi/gitlab). I picked this project for a couple reasons. Primarily, the issues this project had in github seemed both approachable and well described, so I felt that it would something I could do well. Second, I've used Gitlab here and there, so I thought it would be a fun discovery to look in to this gem, what it does, and how it works.

{:.post-content}
To start, I forked the repo and cloned myself a copy (as kindly noted in their CONTRIBUTING.md document). I spent a fair bit of time just clicking through the code. It's a ruby project, not rails, so right off the bat I knew it would take a while longer to get acclimated to what was going on. I can't believe how quickly some of the simple stuff I learned in mod 1 back in August has started to become fuzzy. I'm glad I chose this project to brush up!

{:.post-content}
Part of the project includes confirming or refuting a bug. Great! The issue I chose to work on is from a user who thinks they found a bug. The user is getting an error because they are passing in a data type that the method wasn't handling well, so it's not returning the expected result. After some digging, I can't reproduce the bug. I think I reproduced the scenario the user described, but I am not getting an error. I posted a comment on the issue with my findings and the details of how I tried to reproduce it. I also asked the user for more details about how they found the problem. Perhaps I just didn't follow the right path.

{:.post-content}
Since I still need to make a code contribution, I found another issue on this project to update some API endpoints that have been changed in the newest version of the Gitlab API. I played around with the gem in the terminal and found the problem. I did a "search repository" in github to find all the places that needed to be updated for this endpoint and made the change. Unfortunately the tests now were failing. Luckily updating the tests was pretty straightforward, and once everything was passing, I made the official PR.

{:.post-content}
Honestly, the hardest part of this project was just starting. I felt very intimidated to touch someone else's project. Am I worthy? Am I good enough? I guess it's time to find out!

{:.post-content}
I made my PR tonight, and I'm hoping for one of two results. The best result, of course, would be that my change is merged. Another great alternative would at least be a comment or conversation so I have the opportunity to make changes and try again with a revision. Worst case, it doesn't get merged or get a response, but at least I tried. I learned something new, and I'm slowly conquering the age-old imposter syndrome question "Am I good enough?"
