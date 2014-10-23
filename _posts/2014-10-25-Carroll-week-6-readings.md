---
title: Mapping Networks
date: 2014-10-25
author: Paul Carroll
layout: post
---

Let's begin with my graph visualization. I made use of some of the data on the wiki to create a visualization of a Java program. It looks like this.

![Java top-level view](images/java1.png)

At first glance, you probably can't glean any useful information from this. So why don't I zoom in for you?

![Java mid-level view](images/java2.png)

Are you beginning to see anything interesting? If you know Java, I suspect you can see classes (the big purple nodes). Let's zoom in a little more.

![Java top-level view](images/java3.png)

Yep, there it is! Classes are the big purple nodes, instance variables are the little cyan nodes, and methods are the little green nodes. I'm not sure I learned anything from this visualization, but it was certanly cool.

A few words of discussion on Gephi...did anyone else find the user interface unexpectedly annoying? I had to play around to figure out how to do basic stuff, like zooming in/out. I had to run the program on two separate computers because it didn't work on the first one. Ugh.

The most obvious use of network analysis seems to be analyzing social networks, i.e. letters, which is exactly what the Republic of Letters project is doing. Who was in touch with whom, and when? Did this person have a mutual acquiantance with that person? These are such basic historical questions, and it's cool that network analysis will help us to untangle them. We could also try to map the "company family tree" in Silicon Valley.

But are there any more unexpected uses? I thought it might be cool to map out all the inventions in history. The node at the top is, say, the wheel, which allows us to invent the wheelbarrow, which allows us to invent...and so on. It would be tricky to do this systematically, but super cool. In fact, I kind of want to go do it now, with maybe a thousand of the most important inventions in history.

As for the graph of Silicon Valley, I would love to see someone create a bipartite graph with angel investors and companies. Which angel investors contributed where? I'm sure that there's something interesting to be gleaned from a visualization like that.