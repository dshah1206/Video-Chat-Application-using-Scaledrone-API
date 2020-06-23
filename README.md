# Video-Chat-Application-using-Scaledrone-API
Created in 2018
A simple Peer to Peer Video Chat Application using
i) WebRTC – Web Real Time Communication
ii) Scaledrone- A real time messaging service platform for
signalling service
iii) Google Chrome browser- Any WebRTC supported browser will
work .

Implementation:
In this application there are two users ie. A host and a remote host.
Remote host is also called as offerer.
The application made using html and javascript.
Both the users can individually start their webcams by running the
Html file in a browser.
A hash key is generated every time a user runs the file.
If two users want to get in the same room then the hash key has to
be same. ie. To have a two way communication Hash key works as a
password that can be shared between two users to get into the same
room.
Example:
file:///C:/Users/ABC/Desktop/webrtc-master/index.html#41061d
here #41061d is the hash key
If the same hash key is used in a different location on a different
computer still the network connection will be established.
