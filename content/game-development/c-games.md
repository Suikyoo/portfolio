+++
date = '2026-05-25T01:40:50+08:00'
draft = true
title = 'C Games'
+++

Contrary to popular beliefs, I've had real good fun using C. It's nice to feel like a wizard applying data structure concepts.

## Dating Simulator
Early on 1st or 2nd Year, we had to make a c program. And of course, what's a more appropriate group project than a **dating simulator**?. Anyways, I had my groupmates manually make all the dialogues as binary tree nodes while I just made the entire system for it. 

{{< video
    src="dating-simulator.mp4"
    caption="had to do some weird stuff with the windows terminal to make it render these weird characters"
    loop=true
    muted=true
>}}

This was really vile and primitive. I wasn't all too familiar with C so I guess I used Windows OS to develop this. I had to make a python script that converts my low-resolution drawings into character codes based on a brightness threshold

## C-nake
Compared to the previous one, C-nake is a more *sophisticated* game in a sense that it's more about data structures. This game is a combination of the ***classic snake game + trivia word search + battle royale***.  

{{< figure
    src="/portfolio/cnake.gif"
    caption="**developed for linux devices**, but I was also planning on making a docker file for it to run on other-OS devices as well"
>}}

the snake is basically a **linked list** that constantly eats at the next direction. A recursive function is called every time it *eats at a location* so that:
- the snake's other nodes can eat the one in front of it, simulating **movement**
- it **eats the letter directly in front of it** and make it as part of the linked list

Except for the lazily coded figlet text interface, I'm really satisfied with how this program turned out. 

