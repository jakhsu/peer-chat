# peer-chat

## A exercise project for WebRTC

- Currently using vanilla JS
- Functionality of the app currently is limited to 1-on-1 video calls with the following features:
  - toggle audio
  - toggle video
  - screen sharing (**_not implemented yet_**)
- For signaling I'm currently using [Agora Signaling SDK](https://www.agora.io/en/products/signaling/). However I intend to build a simple signaling server myself soon.
- At the moment this is only for 1-on-1 video calling and if someone gets access to the room id you're on and try to join, one of the attendants will be kicked out of the call. This is certainly not the ideal behaviour even for 1-on-1 calling app so I intend to fix it soon.

## Demo

[Link to demo](https://jackhsu-peerchat.surge.sh/lobby.html)

### How to

1. Once you open the app, you'll see the lobby and an input box for room id, which at the moment is simply any string, e.g., 123chat.
2. If you're trying to **join a call session with someone who's already created a room**, simply put in the id they provided and you'll be connected.
3. If you're **creating a room**, you simply input whatever id you'd like, then you'll be directed to a newly created room. The final step is to let the person you're trying to call know this id so he/she can join.
