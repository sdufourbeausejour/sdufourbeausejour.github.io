---
layout: post
title:  "Hack the planet !"
date:   2017-08-07 12:55:21 -0400
categories: science
tags: conference northern workshop code project
---
I'm back from an exciting week at Stonybrook University (NY). I was there for the [Polar High Performance Computing Workshop and Hackathon][PolarHackathon-Post]. The week kicked off with two days of training. A lot of the courses were from [Software Carpentry][software-carpentry] : [Unix Shell][unix], version control with [Git][git], 4 hours of [Intro to Python][python]... The hands-on coursework developed by this not-for-profit organization is great, and accessible online at no charge. Even after years of coding in Python and using Git, I still learned a couple of tricks - and finally switched to **Python 3** !

The second half of the week was split between hacking time put aside for us to work on our projects and more advanced classes on high-performance computing with [Open Science Grid][OSG] and the [Google Cloud Engine][GCC]. Theses classes came with access codes and free resources for us to burn through with our projects.

It was super motivating to work alongside the other scientists there; I learned a lot and came back energized. As for the science part, well... I spent all week trying to make my java application truly portable. On the last night, when I finally got it running on a Google virtual machine jam-packed full of RAM, I realized that it was still as slow as on my good old 16 Go computer in the lab. Verdict : the [SNAP][SNAP] code which my app is based on just isn't sufficiently parallelized. I used the last two hours of the hackathon to hack a workflow using a parallelized k-means implementation in Python. Fun times ! It reminded me of my physics undergrad and I loved it.

Academic perk : I made a quick stop at the MoMa before flying back home. [#WomenArtistsPostwarAbstraction][MoMa]

[software-carpentry]:https://software-carpentry.org
[unix]:http://swcarpentry.github.io/shell-novice/
[python]:http://swcarpentry.github.io/python-novice-inflammation/
[git]:http://swcarpentry.github.io/git-novice/
[OSG]:https://www.opensciencegrid.org
[GCC]:https://cloud.google.com/products/compute/
[SNAP]:http://step.esa.int/main/toolboxes/snap/
[MoMa]:https://www.moma.org/calendar/exhibitions/3663
[PolarHackathon-Post]:https://www.arcus.org/events/arctic-calendar/27181
