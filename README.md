# WebRTC Intro

Friday - 18th of November, 2016.
The new internet Hype is Real-Time connection. When talking about real-time we find ourselves with the following main categories:

- Data sharing
- Video / Audio streaming
- Socket connection for two-way data flow
- Peer2Peer & Peer2Server2Peer connections

To slowly dive into the tech currently available I leaned on Google, StackOverflow, ... classics ... and several articles and tutorials. The following document tries to be a collection of the resources I found most helpful.

**Warning:** This is not a tutorial series and the links are not ordered in a gradual learning curve specific way.

### Tutorials

- [Google Basic Codelab](https://codelabs.developers.google.com/codelabs/webrtc-web/#0)


### Understanding What is available

- [WebSocket Basics](https://www.html5rocks.com/en/tutorials/websockets/basics/)
- [Connectivity Woes and You](https://xirsys.com/webrtc-connectivity-woes-and-you/): Understanding STUN and TURN servers to solve common issues

### Useful Repos

- [Socket.io](http://socket.io/)
- [Socket.io Streams](https://github.com/nkzawa/socket.io-stream)

### WebRTC 'Solutions'

- [EasyRTC](https://easyrtc.com/)
- [SimpleWebRTC](https://simplewebrtc.com/)
- [RTC-Everywhere](https://github.com/contra/rtc-everywhere)
- [Twilio](https://www.twilio.com/)
- [Kurento](http://www.kurento.org/): Spain based Media Server solution. Aquired by Twilio.

### Blogs

- [WebRTC Hacks](https://webrtchacks.com/)
- [Real world WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/infrastructure/)

### Tools

- [Wireshark](https://www.wireshark.org/): network analyzer
- [Chrome Internals](chrome://webrtc-internals/)
- [Lynckia](http://lynckia.com/): Madrid based openSource project. Looks to offer 'Web Real Time Communications Solutions'

### Screen Sharing

- [Open source chrome extension](https://chrome.google.com/webstore/detail/screen-capturing/ajhifddimkapgcifgcodmmfdlknahffk): Basic extension that can be leveraged from any web page to use the Chrome desktopCapture API. The code is available for download and reuse together with an example library of how to make us of it.
	- [Desktop Capture extension code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/desktopCapture)
	- [Desktop Capture Use](https://github.com/muaz-khan/Chrome-Extensions/tree/master/Screen-Capturing.js)
- [Open source firefox extension](https://github.com/muaz-khan/Firefox-Extensions)
- [Example of screen sharing](https://www.webrtc-experiment.com/getScreenId/)
- [Chrome and Firefox Extension development and testing](https://github.com/opentok/screensharing-extensions)


### Support

- [Is WebRTC Ready?](iswebrtcreadyyet.com)
- [Can I use: RTC](http://caniuse.com/#search=rtc)
- [Can I use: getUserMedia](http://caniuse.com/#search=getUserMedia)