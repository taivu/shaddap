# SHADDAP!

![Screenshot](/documentation/screenshot.png?raw=true "Screenshot")
![Screenshot](/documentation/chat.png?raw=true "Screenshot")

This is a lightweight chat room client built with node.js (express) and socket.io. No additional javascript libraries or frameworks are necessary to run this app (not even jQuery).

Features:
* Randomly generated usernames (adjective + animal) that is assigned to each socket
* Dynamically updated users count for the entire site and individual rooms
* Serverside rendered Handlebars templates
* No frontend frameworks necessary, making it super easy to integrate into your existing webapps

### Directory

Purpose | Location
------------ | -------------
Main application | ./App.js
Server-side socket logic | helpers/socketsmodule.js
Client-side socket logic | publicjavascript/client.js
Misc helpers | helpers/*
Run server | bin/www

### Installation

```
npm install
npm start
```

### License
This software is released under the MIT license.