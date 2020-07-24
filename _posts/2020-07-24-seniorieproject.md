---
title: "Senior Industrial Engineering Project: SJSU Recycling System"
date: 2020-7-24
tags: [business process improvement, six sigma, supply chain, data analytics]
Introduction
excerpt: "R Programming, SJSU Recycling System, Data Science"
---
## Introduction

The concentration of the study is to optimize San Jose State University’s waste management system and reduce their contribution to waste pollution issues in the community. The problems that are found in the system include; large amounts of plastic materials are thrown away; no infrastructure is provided to recycle or reuse the plastic materials; the waiting time to transport the plastic materials to the recycling center is long; a lack of data infrastructure; and, the recycling rate of SJSU Population is 30%.

### Initial Waste Management Supply Chain Flowchart

<img src="{{ site.url }}{{ site.baseurl }}/images/recyclingsystem/processmap.jpeg" alt="">

From inspection of the initial supply chain flowchart, it is apparent that there are various machines, supply chain partners, and people involved in the school's waste management system. One of our industry sponsors and notable system participant, GreenWaste, provided the team with data on which locations on the San Jose State University campus generate the most waste, what types of materials are sent to recycling or landfill, and the amount of truck arrivals per bin type collected. I defined metrics and units, organized, and cleaned up that data on excel before tabulating descriptive statistics and performing a design of experiments test utilizing Minitab and R to identify trends, variation, or factors of significance.

## R Code

Metric: Waste Per Location (Tons)
[link]
(https://github.com/diriyeibrahim/Senior-IE-Project/blob/master/Waste%20Per%20Location.R)

Metric: Materials Recycled Per Month (Tons)
[link]
(https://github.com/diriyeibrahim/Senior-IE-Project/blob/master/Materials%20Recycled%20Per%20Month.R)

Metric: Materials Landfilled Per Month (Tons)
[link]
(https://github.com/diriyeibrahim/Senior-IE-Project/blob/master/Materials%20Landfilled%20Per%20Month.R)

Metric: Bin Removal Frequency (Trucks per Bin)
[link]
(https://github.com/diriyeibrahim/Senior-IE-Project/blob/master/Bin%20Removal%20Frequency.R)
