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
Settings -> Stream ->
Stream Type: Custom Streaming Server
URL: rtmp://localhost/live
Stream key: <The ID of the stream record you have created>
OK
START STREAMING
```



## Built With

* [React] 
* [Redux](https://maven.apache.org/) - For state management
* [Bootstrap](https://rometools.github.io/rome/) - To improve UI

