# peer-chat

## A exercise project for WebRTC

- Currently using vanilla JS
- Functionality of the app currently is limited to 1-on-1 video calls with the following features:
  - toggle audio
  - toggle video
  - screen sharing (***not implemented yet***)
- For signaling I'm currently using [Agora Signaling SDK](https://www.agora.io/en/products/signaling/). However I intend to build a simple signaling server myself soon.


## Demo

[Link to demo](https://jackhsu-peerchat.surge.sh/lobby.html)

### Create a chat room

1. type in any number or text as your chatroom id, e.g., 1234
2. you'll be directed to the newly created chatroom and wait for the other participant to join

### Join an existing chat room

1. type in the chatroom id you wish to join
2. you'll be directed to that room
