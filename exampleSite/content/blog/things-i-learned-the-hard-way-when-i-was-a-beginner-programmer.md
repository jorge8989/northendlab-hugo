+++
author = "Jorge Jr. Arteaga"
categories = ["Software development"]
date = 2020-02-08T04:00:00Z
description = ""
draft = true
image = ""
title = "Things I learned the hard way when I was a beginner programmer"
type = "post"

+++
### Read documentation

When you start programming, it can be fascinating the fact that you can learn a lot, simply by following youtube tutorials.

The problem with this, is that at some point, things won't work exactly as in the tutorials. This can be because the tutorial is out of date, or because you're not using the same operating system, or simply because you missed something from the instructions.

Whatever is the cause, at this point you are on your own. This is where you have to leave youtube and find written instructions for your specific issue. Stackoverflow has the answers to most of our questions. Whatever is the problem we might be facing, chances are, somebody already had it and already wrote a question, and somebody already answered it. However, when we are starting at programming, often times we get stuck with issues relatively simple, that can be solved simply by reading the documentation of the technology that we're learning.

When I was learning Ruby on Rails, years ago, I had a really hard time when I got to the tutorial for uploading files using the Paperclip gem. The tutorial was pretty straight forward. I followed every step (or at least that what I thought), but the gem  wouldn't work!

After days (yes, days) of trying, and even personally asking about my problem to more experienced developers. I decided to sit down, and read the installation section of Paperclip's documentation. It turns out I skipped a step of Paperclip's installation. I had to install a small image processing software on my Windows machine which is dependency of Paperclip. Without it, the gem would never work. The error messages I had didn't mention this, but the documentation did!

After this experience, whenever I'm learning a new technology, I never skip the documentation. In fact, most of the times, when I learn something new, I start with the documentation, and I watch youtube videos or online courses as a complement.

### Don't use Windows

Don't get me wrong, you can build a successful programming career without ever touching a Unix based operating system.

This really depends on the stack that you use. If you happen to work with technologies that run well on Windows, and your work doesn't require you to e.g. deploy apps to Linux based hosting services, and you are fine with it, good for you!

I'm well aware that there are stacks that run without issues on Windows, and of course, some stacks are meant to be used on Windows.