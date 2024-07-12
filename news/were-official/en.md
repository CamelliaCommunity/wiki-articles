---
layout: post
title: A New Wiki
date: 2024-04-09T06:18:00.000Z
category: pages
author: papertek
---
## We are now officially official

Camellia has posted about the Wiki on the server and Twitter! He's made it clear that this is now the official Wiki where you can find information about him, so we developers will try our best to ensure everything is cool.

Because of this announcement, we have been working on some cool things internally, such as a newer *slicker* wiki design, as well as an entire rewrite of the codebase.

## Why are you rewriting?

What an EXCELLENT question! We are rewriting the site because the current codebase has become difficult to manage. In an older news post, I mentioned that the second wiki overhaul was to make things more modular and easier to use. While that has worked for a bit, the wiki is constantly growing (with over 300 articles already), and it will continue to grow since we now have some eyes on us.

Since things were getting more frustrating to fix (the breadcrumbs), we all agreed to switch to a framework called [Vue](https://vuejs.org/). We will also implement other shenanigans and switch entirely off Jekyll (all of this will be documented later).

I'm not sure Jekyll was meant for wiki sites since Jekyll is tailored mostly towards blog posting and documentation. It works slowly as a result, and it's also becoming unreliable.

To give you an example of what kind of monstrous code is in the codebase, look at how breadcrumb navigation works.

![Snippet of the breadcrumb code](/assets/images/uploads/stuidcode.png "Snippet of the breadcrumb code")

This code snippet is only for breadcrumbs like these.

![Breadcrumbs in action](/assets/images/uploads/stupidbreadcrumb.png "Breadcrumbs in action")

As you can see, it's a headache. We want to avoid this in the future, so we hope the rewrite will make us more sane.

## Has there been progress?

Yes! We have made some good progress. We already have some lovely designs to implement for the site and a private testing site where the new wiki is already taking shape!

Check out the latest homepage design!

![New wiki homepage design](/assets/images/uploads/newwikihome.png "New wiki homepage design")

Look at what's been implemented so far! So cool!!!

![Private wiki testing site](/assets/images/uploads/newwikiphoto.png "Private wiki testing site")

We'll update more on progress when things are usable! We will also consider eventually publicizing the repository for developers to play around with.

Stay tuned!
