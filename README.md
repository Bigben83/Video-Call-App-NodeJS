# Simple Video Conference Call
A conference call implementation using WebRTC, Socket.io and Node.js.

## Updated the following
- latest version of Bootstrap
- socket.io.js
- adapter.js
- moment.min.js
- FileSaver.js

## Included additional features
- Whiteboard Share
- Make more touch screen friendly
- Doorbell feature to alert participants that you want to talk

# Getting Started
- Run `npm install`
- `cd src`
- `node app.js`


# Features
- Multi-participants
- Toggling of video stream
- Toggling of audio stream (mute & unmute)
- Screen sharing
- Text chat
- Mute individual participant
- Expand participants' stream
- Screen Recording
- Video Recording
- *Share Whiteboard between participants [new feature]


# Note
You can create a free xirsys account and use their free ice server. You can replace the one used with your own at `src/assets/js/helpers.js`, function `getIceServer()`. The demo may not work as my xirsys account has been deactivated for reasons best known to them (perhaps the hits were too much) and I am not ready to create a new one. Create yours or look for an alternative.


# Alternative
If you prefer to use PHP Web socket (Ratchet) instead of socket.io and NodeJS, check out the PHP version [here](https://github.com/amirsanni/conference-call-ratchet).
