---
layout: post
title:  "Week 1 Report"
date:   2017-05-30 16:16:01 -0600
---

**May30-June4**  
My first task was to extend the data models. I had to represent the message object and room object to have a 1:1 correspondence with the Rocket.Chat internally. 
Then I added support for sending images over the network. The functionality goes like this- let the user select an image from a file, upload it, encode it to base64 to send it over the network, recieve it at the other end, decode it from base64, save the file on a local cache and then finally display it to the client. The backend works perfectly; I'll get to the front end after July.
[Here](https://github.com/WikiToLearn/Ruqola/pull/5) is a link to the code where this part was accomplished.
