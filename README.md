# webrtc-tutorial-demo

Sample WebRTC GetUserMedia and PeerConnection code in a demoable format.  Two JavaScript PeerConnection objects are used in this one page which mimic two browsers in a WebRTC peer to peer audio\video or share session.  

Normally this would be done over two browsers with a server component to relay the WebRTC messages across peers.  I do all this in one web app to make this easier to demo.

This demo is a series of steps which build up both the HTML and JavaScript for a WebRTC Audio and Video or Share PeerConnection demo.  HTML and JavaScript gets displayed on the page as you step through.

To run this all you need to do is deploy the file index.html to any web server and load in either Firefox or Chrome. Best to use HTTPS if you want this to work in Chrome as Chrome requires HTTPS for GetUserMedia.

If H264 is in the list of offered codecs then that codec will get used.

If you want to use window share you need to do these steps

- (Only for Chrome) start chrome browser with flag --enable-usermedia-screen-capturing
- (Only for Firefox) open about:config create  media.getusermedia.screensharing.enabled and set to true
- (Only for Firefox) open about:config in media.getusermedia.screensharing.allowed_domains append the IP address of your web server

Here it is:
https://webrtc-tutorial.000webhostapp.com/
