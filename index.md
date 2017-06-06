---
layout: post
title: Vasudha Mathur 
---

## Ruqola, WikiToLearn, KDE
[Ruqola](https://github.com/WikiToLearn/Ruqola) is a Qt interface to Rocket.Chat, with a library implementing DDP semantics, and a QML UI for both desktop and mobile phones. The application is a QML/C++/Qt app, thus providing multi-platform portability. Currently there is no native Rocket.Chat client; Ruqola will be the first generic chat application based on Rocket.Chat.

This project will consist in designing and developing a chat application for WikiToLearn. New features such as adding notification support through the whole application, creating a more complex model for messages (e.g. support for reactions, images, and advanced features), network management, adding OAuth/federated login support for both desktop and mobile app will be implemented.

## Google Summer of Code 2017

### Before GSoC
I have been working on Ruqola since January this year. My first task was to add notifications support on desktop app. Since I was new to Qt/QML and Rocket.Chat, it took me quite a while to get familiar with the code base and technology. Finally my [PR](https://github.com/WikiToLearn/Ruqola/pull/3) (my first PR ever) got merged into the original code for Ruqola. That felt very satisfying.
There was no looking back from here. I wrote a proposal for Ruqola, got it reviewed by a lot of people, modified, got it reviwed again, and repeated till it looked satisfying enough. While writing the proposal my mentor, Riccardo Iaconelli, told me to write it as how "I" would like it to be and that it's my baby project, I gotta care of it! Ruphy has always been very humble and supportive.

Between the coding, I got to know the WikiToLearn community. I must emphasize on how positive and friendly each one of them is. I still remember the moment how I was welcomed in the community when I joined WikiToLearn Chat; so many unknown people welcoming you with such smiles wanting to know you and help you out. I'm more than happy to be a part of this amazing community. The journey form being welcomed to myself welcoming new people in the community has been incredible (the good part being that it has just started) and gave me a bunch of as amazing friends too.

On May4,2017, I got selected as a student developer in the Google Summer of Code 2017 for project Ruqola under KDE. 

### During GSoc
The first month is for community bonding. I had previously known WikiToLearn peeps so my community bonding included knowing people from KDE and other organizations. The common GSoC groups made the members aware of how diverse students,from 72 countries, will be working with a record 201 open source organizations this summer. That's a huge number.
During this time I and my mentors, Riccardo Iaconelli and Gabriele Lazzaro Falasca, planned out our timeline, set up the phabricator and made our etherpad notes. We decided to first tackle the backend and then the front end. And we were set to roll.

From may30,2017 the coding period started. 

**May30-June4**  
My first task was to extend the data models. I had to represent the message object and room object to have a 1:1 correspondence with the Rocket.Chat internally. 
Then I added support for sending images over the network. The functionality goes like this- let the user select an image from a file, upload it, encode it to base64 to send it over the network, recieve it at the other end, decode it from base64, save the file on a local cache and then finally display it to the client. The backend works perfectly; I'll get to the front end after July.
[Here](https://github.com/WikiToLearn/Ruqola/pull/5) is a link to the code where this part was accomplished.

**June4**  
My next task is to handle network managemnet to make sure the app runs under all network conditions.
  
  
  
  
  
  
  
### [Ruqola](https://github.com/WikiToLearn/Ruqola) <img src="/images/systray.png" alt="Ruqola-Icon" width="25px" height="25px">
