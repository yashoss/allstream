# Smack Chat

## Easy to use video and audio chat application with text chat and picture sharing.

[All Stream](https://allstream.herokuapp.com)

## Instructions:

1. Allow access to camera and microphone
2. Copy your session url and send it to a friend
3. Or open it in a new browser window -- CAUTION for audio feedback
4. Browser should load your local stream and your friend's stream and you
can enjoy speaking to each other, sending messages, and sharing pictures
5. NOTE: Some networks may block streaming services

## Description

A webchat application running in the browser using Google's WebRTC to get and
stream user media. Implements p2p connections using STUN and TURN servers hosted
online. Implements minimal routes and server connections to prevent delay in video
and media connection.

## Technologies Used

* WebRTC
* NodeJS
* javascript
* CSS
* HTML

## WebRTC with STUN and TURN servers

WebRTC is a free, open project that provides browsers and mobile applications with
Real-Time Communications (RTC) capabilities via simple APIs.

A setback to IP and Video connectivity has been the restriction NATs and firewalls
pose to reliable call completion. IETF standards STUN, TURN and ICE were developed to address the NAT traversal problem.

* STUN helps connect IP end-points.
* TURN assist in the discovery of paths between peers on the Internet

## To-Dos

1. Allow conference call capabilities
2. Integrate into messaging application
3. Switch to cross-platform desktop application
