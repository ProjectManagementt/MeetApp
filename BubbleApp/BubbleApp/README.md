# Bubble chat

Free `WebRTC` browser-based video calls, chat, and screen sharing, using google Stun and [numb](http://numb.viagenie.ca/) Turn. `Bubble Chat` provides video quality and latency not available with traditional technology.

Open the app with the following **supported browsers** and many more.

[![browsers](public/images/browsers.png)](https://mirotalk.herokuapp.com/)



<br>



## Features

-   Is `100% Free` - `Open Source` - `Self-hosted`
-   No download, plug-in, or login required, entirely browser-based
-   Unlimited number of conference rooms without call time limitation
-   Possibility to Lock/Unlock the Room for the meeting
-   Desktop and Mobile compatible
-   Optimized Room URL Sharing (share it to your participants, wait for them to join)
-   Webcam Streaming (Front - Rear for mobile)
-   Audio Streaming crystal clear + detect speacking and indicator
-   Screen Sharing to present documents, slides, and more...
-   File Sharing, share any files to your participants in the room
-   Select Audio Input - Output && Video source
-   Ability to set video quality up to 4K and 60 FPS
-   Recording your Screen, Audio and Video
-   Snapshot the video frame and save it as image png
-   Chat with Emoji Picker & Private messages & Save the conversations
-   Speech recognition to send the speeches
-   Advance collaborative whiteboard for the teachers
-   Share any YT Embed video in real-time
-   Full-Screen Mode on mouse click on the Video element
-   Possibility to Change UI Themes
-   Right-click on the Video elements for more options
-   Direct `peer-to-peer` connection ensures the lowest latency thanks to `WebRTC`
-   Supports [REST API](app/api/README.md) (Application Programming Interface)

## Presentation

https://www.canva.com/design/DAE693uLOIU/view

## Demo

-   `Open` Bubble Chat
-   `Pick` your Room name and Join
-   `Allow` using the camera and microphone
-   `Share` the Room URL and Wait for someone to join for the video conference

## Direct join

-   You can also `join` directly to your `room` by going to:
-   https://mirotalk.up.railway.app/join?room=test&name=mirotalk&audio=0&video=0&notify=0
-   https://mirotalk.herokuapp.com/join?room=test&name=mirotalk&audio=0&video=0&notify=0

    | Params | Type    | Description      |
    | ------ | ------- | ---------------- |
    | room   | string  | room Id          |
    | name   | string  | user name        |
    | audio  | boolean | enable / disable |
    | video  | boolean | enable / disable |
    | notify | boolean | enable / disable |

## Embed a meeting

Embedding a meeting into a service or app using an iframe.

```html
<iframe
    allow="camera; microphone; fullscreen; display-capture; autoplay"
    src="https://mirotalk.up.railway.app/newcall"
    style="height: 100%; width: 100%; border: 0px;"
></iframe>
```

## Quick start

-   You will need to have `Node.js` installed, this project has been tested with Node version [12.X](https://nodejs.org/en/blog/release/v12.22.1/) and [14.X](https://nodejs.org/en/blog/release/v14.17.5/)

```bash
# clone this repo
$ git clone https://github.com/miroslavpejic85/mirotalk.git
# go to Bubble Chat dir
$ cd mirotalk
# copy .env.template to .env
$ cp .env.template .env
# install dependencies
$ npm install
# start the server
$ npm start
```

-   Open http://localhost:3000 in browser

---

## Docker

-   Install docker engine: https://docs.docker.com/engine/install/
-   Install docker compose: https://docs.docker.com/compose/install/

```bash
# copy .env.template to .env
$ cp .env.template .env
# build or rebuild services
$ docker-compose build
# create and start containers
$ docker-compose up # -d
# stop and remove resources
$ docker-compose down
```

-   Open http://localhost:3000 in browser

---

## Setup Turn

`Recommended`, for more info about the Turn check out [here](https://webrtc.org/getting-started/turn-server).

---


## Commercial License or closed source

For commercial use or closed source projects, we can offer licensing under the following terms.

> World-wide, non-exclusive, non-transferable and non-sub-licensable license of MiroTalk as is on https://github.com/miroslavpejic85/mirotalk for use in purchasers products, as long as the resulting software does not stand in concurrence to the MiroTalk itself. Any liability is excluded. The law of the Federal Republic of Italy shall apply exclusively.

The one time fee is 499 EUR net. Please contact miroslav.pejic.85@gmail.com.

---

<br>
