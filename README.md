# RTP VideoStreamer

Video streaming server and client project using RTP and RTPS protocol, coded in Java. The project was conceived for the discipline of Computer Networks 2 in the year 2023 at the Federal University of Uberlândia.

To compile:

  `javac Server.java`
  
  `javac Client.java`
 
To run:
  
  `java Server <server_port>`
  
  The server_port parameter should be > 1024.
  
  `java Client <server_address> <server_port> <video_file>`
  
  The server_address is 127.0.0.1 (in general), server port is the same specified in the Server command and video_file is a sample file to be transmitted.
