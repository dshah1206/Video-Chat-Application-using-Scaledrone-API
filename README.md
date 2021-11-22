# Computer Networks Project: Video-Chat-Application-using-Scaledrone-API
The project was created in 2018. The application is a simple peer-to-peer video chat application that uses three resources:

1) WebRTC - Web Real Time Communication Framework.
2) Scaledrone - A real time messaging service platform for signalling service.
3) Any WebRTC supported browser (Recommended: Google Chrome). 

## Implementation Process:

In this application, there are two users, i.e. a host and a remote host. Remote hosts are also known as offerers. The application is written using HTML and JavaScript. Both users can start their webcams individually by running the HTML file in a browser. Every time a user runs the file, a hash key is generated. If two users want to get into the same room, the Hash key must be the same, i.e. a two-way communication. The Hash key works as a password that can be shared between two users in order to get into the same room.
*For Example:
file:///C:/Users/ABC/Desktop/webrtc-master/index.html#41061d*

    a) In the above url: #41061d is the hash key

If the same hash key is used in a different location on a different computer still the network connection will be established.

