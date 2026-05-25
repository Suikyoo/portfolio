+++
date = '2026-05-25T02:47:36+08:00'
draft = true
title = 'Networking and Concurrency'
+++

Imma be honest, this chapter is **dedicated solely to Go**. It is such a beautiful language with such a unique paradigm especially with goroutines which makes it so much easier to spawn threads in a program. 


## Go Chat

a messaging program that can handle multiple clients. 

{{< video
    src="go-chat.mp4"
    caption="this allows multiple clients to connect, just like a group chat"
    loop=true
    muted=true
>}}

This uses a basic client-server architecture. The server listens for connection and creates another thread as well as a socket once a client connects.

## Load Balancer

This came out of **Rob Pike**'s discussion on Go, and I figured I might as well give it a try on my own. 

![](/portfolio/load-balancer.jpg)
