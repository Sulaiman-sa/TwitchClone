# Twitch Clone
React application that implements Streaming functionality using Real-Time Messaging Protocol (RTMP).
Each user can create any number of records (Streams) and will be able stream to those records using OBS software.


### Prerequisites

To stream you need to install OBS for your operating system 

https://obsproject.com/


## Getting Started
First clone the project then:
```
cd api
npm install
npm start
-
cd rtmpserver
npm install
npm start
-
cd client
npm install
npm start
```
Then open localhost:3000 and sign in using google Auth and create a record.  
Now go to OBS
```
Sources -> + -> Display Capture (or whatever you want to stream)
-
Settings -> Stream 
Stream Type: Custom Streaming Server
Server: rtmp://localhost/live
Stream key: <The ID of the stream record you have created>
OK
START STREAMING
```

Your Streaming will be available at the record page you have created  
http://localhost:3000/streams/<Your record ID>


## Built With

* [React] 
* [Redux]- For state management
* [reactstrap] - To improve UI

