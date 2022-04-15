# Video-Chat-App-
A "Discord clone" with Socket.io, Node.js, Express &amp; MongoDB... Create Room, invite other people to your Room, chat with…

<img width="603" alt="discord" src="https://user-images.githubusercontent.com/101202952/163559556-b661b0a1-8924-4130-8adc-c1b957aed8c7.PNG">

## Overview

Video Chat App is a clone of the popular chat app Discord. Users are able to create and join room, send and accept/reject friend requests, create rooms with audio call possibility and message each other through text channels or through direct messaging.

**This project is not currently maintained.**

##  Technologies Used

```
 Build A Discord Chat App with MERN stack and REDUX
 
 Server Side packages:
 MongoDB: Our Main Database
 Express: Our NodeJS framework
 NodeJS: Used to create the server
 Socket.io: Used for real-time communication
 
 Client Side packages:
 ReactJS: Our Js Library to create UI components.
 Socket.io: Used for real-time communication (client side)
 Web RTC: Used for videochat and audio call possibilities.

***************************
Author: Helitha Rupasinghe
Licence: MIT
Credit: Marek Gryszkiewicz (Web Developer)
```

## 💾 Installation

```
# clone the repo
$ git clone https://github.com/JavascriptDon/Video-Chat-App-.git

$ cd discord-clone

# install the node modules...
$ npm install

# start
$ npm start

```

Create an .env file and set the variables for the backend like so...

```
API_PORT= YOUR_PORT_NUMBER_
MONGO_URI= YOUR_MONGODB_URI_
TOKEN_KEY= yoursecretkeygoeshere

```

## Features

#### Users 
- Real time messaging using Socket IO

#### Private Messaging
- Users receive direct messages
- Users can send direct messages by clicking on a users avatar or username
- Users can remove direct messages without losing their message history (TBC)

#### Friend Requests 
- Users can accept or reject friend requests
- Friend requests are sent in real time
- Users can cancel outgoing friend requests
- Users can see who is online/offline 
- Users can accept or cancel incoming friend requests
- Users can remove friends from their friends list (TBC)


#### Servers
-  Users can create a new Room (the user is then the admin of that Room)
-  Rooms are created with audio call possibility
-  Users can join an existing Room
-  Users can close & delete the room if they are admin.
-  Users can see all the other members in the room. 


-  
-  Local Authentication
-  Loads User Data upon login (Rooms, Channels, Private Messages)
-  Creation and Joining Rooms
-  Room Settings (Changes between Camera, Mic, ScreenShare and deletion of room)
-  Persistent channel history
-  Private messaging
-  Timestamps for messages
-  Show current active users in given Room
-  Voice Chat (Buggy, but main features work)


<img width="945" alt="video" src="https://user-images.githubusercontent.com/101202952/163565486-5035e88c-38b8-4ffd-ac2c-44d4789cbafa.PNG">

