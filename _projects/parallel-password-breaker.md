---
title: "Parallel Password Breaker"
excerpt: "Websocket server leverages clients to crack passwords."
header:
  image: /assets/imgs/inaction.jpg
  teaser: assets/imgs/password.png
sidebar:
  - title: "Role"
    text: "Back End, Documentation"
  - title: "Responsibilities"
    text: "Writing Javascript code and Documentation"
---

A project done for my Parallel Programming class, the parallel password breaker allows any computer to host a server that can generate any string of 4 lowercase alphabetical characters, create the sha256 hash for those characters, and then allow any number of clients to work on a particular section of possible 4 character strings from 'aaaa' to 'zzzz' until the correct hash is found. You can see the project in action above- I have three different client command prompts connecting to a server command prompt with each of the three clients working on a section of the 456,976 possibilities of 4 character alphabetical strings until they find the randomly generated password.

Of course, it should be stated that while in the above instance the program is ran on my desktop computer alone, any number of other clients using different machines can connect as well. 

I worked on code within passwordReceiver/Sender as well as writing some small documentation not included in the github. You can find the source code for this project [here](https://github.com/parkergray221/Coursework/tree/master/CSC%20698%20-%20Parallel%20Programming/Term%20Project%20-%20Parallel%20Password%20Breaking).
