---
layout: post
title: Outreachy post 3 - Midterm report
date: 10.01.2020 19:30
categories: outreachy debian
image: outreachy.png
tags: [outreachy, debian]
---

Time passes by quickly when you do the things that you like. And so have passed by very quickly the first six weeks of
[Outreachy](https://www.outreachy.org/). The first half of the internship has been an amazing experience for me. I have worked and learned so
many new things. I got familiar more closely with the Debian project that I was already contributing to in the past, but less intensively. I
am very happy to get to know more people from the community, feel so welcomed and find such a warm environment.

Since the first weeks of the internship I started working on fundraising materials for [DebConf20](https://debconf20.debconf.org/) as part of
my tasks, using LaTeX which is an amazing tool to work on creating different types of documents. My skills on using LaTeX are improved, and
the more I use it the more I discover how powerful a tool it is and the variety of things that you can do with it. Lately I worked on the
flyer and brochure that will be sent to potential sponsors.

![DebConf20 sponsorship flyer](/assets/images/dc20-sponsorship-flyer.png){:class="img-responsive"}

On the flyer I removed the translation elements, since this year the materials will be only in English. I updated the content making it
relevant for this year, and also updated the logo to the winning entry of [a contest](https://wiki.debian.org/DebConf/20/Artwork/LogoProposals)
the local team ran. Matching to the dominant color of the DebConf20 logo I created a color scale that we are using for headlines and decorative
elements within the fundraising material and the conference web page.

![DebConf20 color scale](/assets/images/dc20-color-scale.png){:class="img-responsive"}

As for the fundraising brochure, I took the content from a Google doc, which was carefully created by my mentor Karina and converted it into
LaTeX. I adapted it with the new logo, colors and monetary values in the local currency. For this I needed to create a TeX `\newcommand` as
the ILS currency symbol (₪) is not supported natively. This also led to a restriction in the choice of fonts available because the ILS symbol
needs to be part of the font. With support from the wider DebConf team we settled on Liberation Sans. As we are working on the visual identity
of DebConf20, we are almost finalizing the fundraising materials for this edition.

I have also worked on the draft email templates that I have proposed for the next phases of contacting sponsors, hoping I will receive a good
feedback from the team. They are available on a private DebConf git repo. The basic idea is to provide new aspects of the benefits of
sponsoring a DebConf with each contact that we have reaching out to sponsors.

[![Initial commit of the DebConf20 sponsorship brochure](/assets/images/dc20-brochure-commit.png){:class="img-responsive"}](https://salsa.debian.org/debconf-team/public/data/dc20/commit/6af9a117ffc1bafc84a7edca2c86c02a93783a89)

Beside practicing LaTeX I have also worked a lot on git and it has been very helpful for me to practice. There is so much information to work
on and so much you can do with git. I am trying to get beyond the common level of understanding git:

[![xkcd on git](/assets/images/xkcd-git.png){:class="img-responsive"}](https://xkcd.com/1597/)

Another task I have is documentation, so, I have worked on this too, in parallel. As each DebConf is organized every year in another country,
you might imagine that for the local team not everything is familiar, even if they might be part of Debian, and of course depending also on
the experience they might have on organizing events or specifically fundraising. So, working on fundraising now, I have had many things that I
was not completely familiar with and I have started documenting the workflow so it will be hopefully more convenient and smooth process for
future DebConf local organizing teams.

As mentioned on my [last blog post](/2019/12/20/outreachy-post-2/), I have already joined the main communication channels that the Debian community uses. I try to be as much
available as I can and try to stay updated with all the info that might be relevant information for my internship. I participate in all the
biweekly team meetings for DebConf20, giving updates about my progress and staying in the loop of the current situation regarding
organizational topics related to the conference.

[![Updating the DebConf20 sponsorship flyer in git](/assets/images/dc20-flyer-commit.png){:class="img-responsive"}](https://salsa.debian.org/debconf-team/public/data/dc20/commit/80fcdfedae98fe823ddb46119181709766a4bbb6)

I stay in contact with my mentors Daniel and Karina via IRC and emails. I would like to take a moment and thank them for all their
encouragement, support and feedback which has helped me improve and has motivated me a lot to continue working in this awesome project. I keep
connection to the wider community as well via IRC, [Planet Debian](https://planet.debian.org/) or constantly following the [mailing lists](https://lists.debian.org/debconf.html).

Last but not least, I also participate in the Outreachy webchats where I had the chance to have a little bit of background from other
Outreachy interns and meet the people who are running the Outreachy program. I am so glad to see what a safe, easygoing and inclusive
environment they have created for everyone.

My experience so far has been a blast!
