# webrtc-tutorial-demo

Sample WebRTC GetUserMedia and PeerConnection code in a demoable format.  Two PeerConnections are in this one page which mimic two browsers in a WebRTC peer to peer session.  Normally this would be over two browsers with a server component to relay the WebRTC messages across peers.  I do all this in one web app to make this easier to demo.

This demo is a series of steps which builds up both the HTML and JavaScript for a WebRTC Audio and Video PeerConnection demo.  HTML and JavaScript gets displayed on the page as you step through.

To run this all you need to do is deploy the file index.html to any web server and load in either Firefox or Chrome. Best to use HTTPS if you want this to work in Chrome as Chrome requires HTTPS for GetUserMedia.

If H264 is in the list of offered codecs as in the case of Firefox then that codec will get used.
