---
layout: post
title:  "The Fastest Way I Know To Render With SDL"
---

I am writing a game and, for reasons I may explain in further posts, it uses a software renderer. 
I chose to use SDL as the graphics interface becasue it is popular, mature and simple. Because I 
am very good at avoiding working on the actual game, I spend most of my time tinkering with the 
internals rather than the gameplay, and because I like things that go fast I want to find the 
fastest way (for a software renderer) to draw stuff to the screen.

Here's how SDL works:


